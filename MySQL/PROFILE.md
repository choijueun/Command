### Profile 설정

    SELECT @@profiling;

0: OFF

1: ON

    SET profiling = 1;
    SET @@profiling_history_size = 100;

profiling_history_size default: 15

min~max: 0 to 100

<br/>

### Profile 조회

    SHOW PROFILES;
    SHOW PROFILE ALL FOR QUERY (Query_ID)
