## Привет! Я Наталия Тарасова 👋

- Data Engineer, превращаю сырые данные в структурированные и полезные ресурсы для аналитики и бизнеса
- Готова к сотрудничеству
*********

### Languages and tools

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" 
title="js" width="40" height="40" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original-wordmark.svg"
title="js" width="40" height="40" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apacheairflow/apacheairflow-original-wordmark.svg"
title="js" width="40" height="40" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jupyter/jupyter-original-wordmark.svg"
title="js" width="40" height="40" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg"
title="js" width="40" height="40" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apachespark/apachespark-original-wordmark.svg"
title="js" width="60" height="60" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original-wordmark.svg" 
title="js" width="60" height="60" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/hadoop/hadoop-original-wordmark.svg" 
title="js" width="60" height="60" />&nbsp;   
***********


### 🔄 ETL Pipeline example
```mermaid
flowchart LR
    %% Источники данных
    A[📥 Источник данных: CSV / JSON / API] --> B[☁️ Загрузка в облачное хранилище (S3)]
    
    %% Трансформация
    B --> C[🧹 Очистка и нормализация данных]
    C --> D[🔄 Обогащение данных / агрегирование]
    
    %% Хранилище
    D --> E[💾 Загрузка в базы данных: PostgreSQL]
    E --> F[🏗️ Построение аналитических витрин (ClickHouse, Greenplum)]
    
    %% Анализ и визуализация
    F --> G[📊 Визуализация: Superset / Metabase]

    %% Стили
    classDef source fill:#f9f,stroke:#333,stroke-width:2px;
    classDef transform fill:#ff9,stroke:#333,stroke-width:2px;
    classDef storage fill:#9f9,stroke:#333,stroke-width:2px;
    classDef analytics fill:#9ff,stroke:#333,stroke-width:2px;

    class A,B source;
    class C,D transform;
    class E,F storage;
    class G analytics;
```

Данная диаграмма показывает типовой ETL-процесс, реализованный мной в проектах.


********



          
          




