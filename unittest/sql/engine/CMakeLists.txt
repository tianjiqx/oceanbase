sql_unittest(test_exec_context)
sql_unittest(test_phy_operator)
sql_unittest(test_engine)
sql_unittest(test_physical_plan)
sql_unittest(test_empty_table_scan)
sql_unittest(test_sql_fixed_array)

add_subdirectory(aggregate)
add_subdirectory(dml)
add_subdirectory(subquery)
add_subdirectory(expr)
add_subdirectory(set)
add_subdirectory(px)
add_subdirectory(basic)
add_subdirectory(sort)
add_subdirectory(join)
add_subdirectory(monitoring_dump)
