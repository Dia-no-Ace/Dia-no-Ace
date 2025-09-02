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
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original-wordmark.svg"
title="js" width="60" height="60" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original-wordmark.svg" 
title="js" width="60" height="60" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/hadoop/hadoop-original-wordmark.svg" 
title="js" width="60" height="60" />&nbsp;   
***********


### 🔄 ETL Pipeline example
```mermaid
flowchart TD
    %% Источники данных
    A[📥 Источник данных: CSV / JSON / API] --> B[⚙️ Трансформация данных]
    
    %% Трансформация
    B --> C[🧹 Очистка и нормализация данных]
    C --> D[🔄 Обогащение данных / агрегирование]
    
    %% Хранилище
    D --> E[💾 Загрузка в базы данных: PostgreSQL / MySQL]
    D --> F[☁️ Облачное хранилище: BigQuery / S3]

    %% Анализ
    E --> G[📊 Анализ и визуализация: Jupyter / Matplotlib / Seaborn]
    F --> G

    %% Стили
    classDef source fill:#f9f,stroke:#333,stroke-width:2px;
    classDef transform fill:#ff9,stroke:#333,stroke-width:2px;
    classDef storage fill:#9f9,stroke:#333,stroke-width:2px;
    classDef analysis fill:#9ff,stroke:#333,stroke-width:2px;

    class A source;
    class B,C transform;
    class D,E,F storage;
    class G analysis;
```markdown
> Эта диаграмма показывает стандартный ETL-процесс.


********



          
          




