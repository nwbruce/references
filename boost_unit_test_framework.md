# Boost Unit Test Framework Quick Reference

`*` is one of (`WARN`, `CHECK`, `REQUIRE`)

## Basics
Macro | Description
--- | ---
`BOOST_*( predicate )` | 
`BOOST_*_MESSAGE( predicate, message )` | 
`BOOST_*_PREDICATE ( predicate, args )` | 
`BOOST_ERROR( message )` | 
`BOOST_FAIL( message)` | 

## Comparisons
Macro | Description
--- | ---
`BOOST_*_EQUAL ( left, right )` | 
`BOOST_*_BITWISE_EQUAL ( left, right )` | 
`BOOST_*_NE ( left, right )` | 
`BOOST_*_LT ( left, right )` | 
`BOOST_*_LE ( left, right )` | 
`BOOST_*_GT ( left, right )` | 
`BOOST_*_GE ( left, right )` | 
`BOOST_*_CLOSE ( left, right, percent_tolerance )` | 
`BOOST_*_CLOSE_FRACTION ( left, right, tolerance )` | 
`BOOST_*_SMALL` | 
`BOOST_*_EQUAL_COLLECTIONS ( left_begin, left_end, right_begin, right_end )` | 

## Exceptions
Macro | Description
--- | ---
`BOOST_*_THROW ( statement, exception_type )` | 
`BOOST_*_EXCEPTION ( statement, exception_type, predicate )` | 
`BOOST_*_NO_THROW ( statement )` | 
