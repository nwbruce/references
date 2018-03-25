# Boost Unit Test Framework Quick Reference

`_CHECK` below can also be `_WARN`, or `_REQUIRE`

## Basics
Macro | Description
--- | ---
`BOOST_CHECK ( predicate )` | 
`BOOST_CHECK_MESSAGE ( predicate, message )` | 
`BOOST_CHECK_PREDICATE ( predicate, args )` | 
`BOOST_ERROR ( message )` | 
`BOOST_FAIL ( message)` | 

## Comparisons
Macro |
--- |
`BOOST_CHECK_EQUAL ( left, right )` | 
`BOOST_CHECK_BITWISE_EQUAL ( left, right )` | 
`BOOST_CHECK_NE ( left, right )` | 
`BOOST_CHECK_LT ( left, right )` | 
`BOOST_CHECK_LE ( left, right )` | 
`BOOST_CHECK_GT ( left, right )` | 
`BOOST_CHECK_GE ( left, right )` | 
`BOOST_CHECK_CLOSE ( left, right, percent_tolerance )` | 
`BOOST_CHECK_CLOSE_FRACTION ( left, right, tolerance )` | 
`BOOST_CHECK_SMALL ( value, tolerance )` |
`BOOST_CHECK_EQUAL_COLLECTIONS ( left_begin, left_end, right_begin, right_end )` | 

## Exceptions
Macro | Description
--- | ---
`BOOST_CHECK_THROW ( statement, exception_type )` | 
`BOOST_CHECK_EXCEPTION ( statement, exception_type, predicate )` | 
`BOOST_CHECK_NO_THROW ( statement )` | 
