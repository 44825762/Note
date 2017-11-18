# Note
###distinct:关键词 DISTINCT 用于返回唯一不同的值,要求目标表Table必须存在，并且字段也必须存在
eg:SELECT DISTINCT 列名称 FROM 表名称
eg:insert into table_a(field_a1,field_a2,field_a3) select field_b1,field_b2,field_b3) from table_b

###sys_guid():oracle函数，用于生成唯一guid
eg:update VARIETY_PROMOTION_DETAILS set id = sys_guid()
