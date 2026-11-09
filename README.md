# Olist-E-Commerce-Data-Analysis-Business-Insights-Postgre-SQL-PowerPoint-
A comprehensive SQL-driven analysis of the Olist Brazilian E-Commerce dataset. This project evaluates revenue trends, logistic bottlenecks, product category performance, and customer satisfaction to deliver actionable strategic recommendations.

📊 Key Findings & Business Impact

Financial Performance & AOV:

Monthly revenue demonstrates a strong, stable upward trend across the analyzed period.

Average Order Value (AOV) remains exceptionally stable at ~$ 153.25, indicating consistent basket sizes regardless of seasonal volume growth.

Logistics & Customer Satisfaction:

Olist operates under a conservative estimation model (Under-promise & Over-deliver): actual delivery times are roughly 2x faster than estimated dates.

While 92% of orders are delivered on time, the 8% late deliveries severely impact customer experience, driving average review scores down from 4.3 ★ to 2.6 ★.

Product Matrix:

The beleza_saude (Health & Beauty) category dominates as the #1 revenue generator, supported by daily essentials and personal care items.

Geographical Concentration:

Extreme regional bias: 41% of all marketplace orders originate from a single state — San Paulo (SP) (Top-3 states account for over 60%).

💡 Strategic Recommendations

Implement Delay Alert Systems: Establish a proactive tracking system for at-risk orders. Alerting customers with compensatory vouchers prior to delivery reduces negative 1-star reviews.

SP Fulfillment Optimization: Capitalize on the 41% volume in São Paulo by establishing localized fulfillment hubs for Same-Day / Next-Day delivery.

Scale Core Categories: Expand seller acquisition in Health & Beauty while cross-promoting secondary high-performing categories like Home & Bath.

🛠️ Technical Implementation & Stack

Database Engine: PostgreSQL

SQL Techniques: CTEs, Window Functions (OVER, SUM() OVER), DATE_TRUNC, Multi-Table JOINs, Data Aggregations, CASE conditional logic.

EDA & Data Architecture Handling:

Resolved the dataset's unique entity schema: distinguishing transactional customer_id from persistent customer_unique_id.

Cleaned non-representative partial months (boundary cut-offs) to ensure accurate trend analysis.

📁 Repository Structure

📄 olist_analysis.sql — Clean, well-commented SQL script covering EDA, revenue metrics, logistics performance, and regional breakdown.

📊 olist_business_presentation.pptx — Executive 5-slide presentation tailored for business stakeholders.

🇷🇺 Описание проекта на русском языке (Russian Version)

Комплексный SQL-анализ данных бразильского маркетплейса Olist с целью поиска точек роста бизнеса, оптимизации логистики и подготовки стратегических рекомендаций для менеджмента.

📊 Ключевые результаты

Финансы: Устойчивый рост выручки при стабильном среднем чеке ~$ 153.25.

Логистика: 92% доставок выполняются в срок, однако 8% задержек снижают средний рейтинг заказа с 4.3 до 2.6 звезд.

Товары: Категория beleza_saude (Красота и здоровье) — абсолютный лидер по выручке.

География: 41% всех заказов маркетплейса сконцентрированы в штате Сан-Паулу (SP).

🛠️ Стек

PostgreSQL (SQL: CTE, оконные функции, DATE_TRUNC, сложные агрегации), PowerPoint.

👤 Author / Valeriia Galinskaia

Data Analyst | E-Commerce Analytics Project
