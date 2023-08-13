### 约定

#### 代码提交规范
- Style guide:
    - [Google Go Style](https://google.github.io/styleguide/go/)
    - [Uber](https://github.com/uber-go/guide/blob/master/style.md)

- Commit messages: https://www.conventionalcommits.org

#### 数据库索引
- PostgreSQL index naming: https://gist.github.com/popravich/d6816ef1653329fb1745
- gorm也有一套规范
  1. 一般索引是 `idx_tableName_on_column`, 例如 idx_messaging_records_on_source
  2. 联合索引一般是`idx_tablename_on_column1_column2`，idx_messaging_records_on_user_scheduled_at
  3. 唯一索引一般是 `uix_tablename_column`
  4. 主键一般是 `tablebname_pkey`

