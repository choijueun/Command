# Optimizer

    SHOW VARIABLES LIKE 'optimizer_trace';

    SET OPTIMIZER_TRACE = 'enabled=on';
    SET OPTIMIZER_TRACE = 'enabled=off';

### 확인

    SELECT * FROM INFORMATION_SCHEMA.OPTIMIZER_TRACE;