# datawarehouse-ssis-2023

<h2>Que es un Datawarehouse ?</h2>
<p>es un sistema de almacenamiento de información diseñado para consolidar, integrar y analizar grandes volúmenes de datos provenientes de diferentes fuentes. Su objetivo principal es apoyar la toma de decisiones empresariales mediante el análisis de datos históricos y actuales.</p>
<p>Hoy en día, prácticamente todas las empresas se están moviendo a la nube debido a Razones lucrativas como la ausencia de costos iniciales, posibilidades de escala infinita, alto rendimiento, y así sucesivamente. Las empresas que almacenan datos confidenciales que no pueden trasladarse a la nube se puede elegir un enfoque híbrido. La nube de Microsoft (también conocido como Azure) proporciona tres tipos de servicios.</p>
<p>Microsoft Azure ofrece una amplia gama de servicios en la nube para el análisis de datos. Podemos categorizarlos ampliamente bajo almacenamiento y cómputo:</p>
<ul>
  <li>Azure SQL Data Warehouse</li>
  <li>Azure Blob Storage</li>
  <li>Azure Data Lake Storage</li>
  <li>Azure Data Lake Analytics</li>
  <li>Azure Analytics Services</li>
  <li>Azure Databricks </li>
</ul>

<h2>Azure Data Factory</h2>
<p>Azure Data Factory (ADF) es un servicio de integración de datos basado en la nube que actúa como pegamento en su solución de macrodatos o análisis avanzado, lo que garantiza que sus flujos de trabajo complejos se integren con los diversos servicios dependientes </p>
<img width="975" height="468" alt="image" src="https://github.com/user-attachments/assets/b2ff714a-6112-4311-a49f-c6b38115c690" />


<h2>Por que es importante el big data ?</h2>
<p>Los datos son la nueva moneda. Los volúmenes de datos han aumentado drásticamente con el tiempo. Los datos se generan a partir de sistemas tradicionales de punto de venta, aplicaciones modernas de comercio electrónico, fuentes sociales como Twitter e IoT sensores/wearables de todo el mundo. El reto para cualquier organización Hoy es analizar este conjunto de datos diverso para tomar decisiones más informadas que son predictivos y holísticos en lugar de reactivos y desconectados</p>

<h2>Que es SSIS</h2>
<p>SSIS es una plataforma extensible para construir soluciones ETL complejas. Se incluye con SQL Server y consta de un servicio de Microsoft Windows® que gestiona la ejecución de flujos de trabajo ETL, junto con herramientas y componentes para desarrollarlos. <br><br>
Además del servicio de Windows de SSIS, SSIS incluye: <br>
</p>
<ul>
  <li>SSIS Designer. Una interfaz gráfica de diseño para desarrollar soluciones de SSIS en el entorno de desarrollo de Microsoft Visual Studio®. Por lo general, se inicia     la aplicación SQL Server Data Tools (SSDT) para acceder a esto.</li>
  <li>Asistentes. Utilidades gráficas que puedes utilizar para crear, configurar y implementar rápidamente soluciones de SSIS.</li>
  <li>Herramientas de línea de comandos. Utilidades que puedes utilizar para administrar y ejecutar paquetes de SSIS.</li>
</ul>

<h2>Esquematico del proyecto a realizar</h2>
<img width="975" height="423" alt="image" src="https://github.com/user-attachments/assets/b7552b58-faca-4aa1-92a8-86c775a0184d" />


<h2>Modelo dimensional de la base de datos en azure</h2>
<img width="405" height="272" alt="image" src="https://github.com/user-attachments/assets/e993dd14-f254-4518-a4f3-5327415dac21" />
<img width="1170" height="807" alt="image" src="https://github.com/user-attachments/assets/5a9dcc7b-bd59-454c-bd49-ac350e50a788" />


<h2>Carga satisfactoria de todas las tablas</h2>
<img width="984" height="479" alt="image" src="https://github.com/user-attachments/assets/fda13363-54af-4346-b743-bca992928f76" />

<h2>Configuracion de la limpieza de la base de datos.</h2>
<img width="674" height="613" alt="image" src="https://github.com/user-attachments/assets/69364e77-d7aa-45a8-bad6-a6dac903f198" />


<h2>Carga de la  tabla DimEmployees</h2>
<img width="1389" height="445" alt="image" src="https://github.com/user-attachments/assets/3fabe1be-3b64-438b-80e8-f64ba790da05" />
<img width="565" height="604" alt="image" src="https://github.com/user-attachments/assets/e49ecbf5-5334-4099-ac5b-4dad9ad57fe9" />
<img width="687" height="553" alt="image" src="https://github.com/user-attachments/assets/44177e9c-0e43-4135-ba69-12e342e1a090" />

<h2>Carga de la tabla DimShippers</h2>
<img width="992" height="508" alt="image" src="https://github.com/user-attachments/assets/a4ac20da-c3d3-481c-966d-73845ebc585b" />
<img width="580" height="618" alt="image" src="https://github.com/user-attachments/assets/da0c0f8c-4c23-4182-817f-2b84a3b2739f" />
<img width="692" height="603" alt="image" src="https://github.com/user-attachments/assets/627d95ec-1ed6-4477-a125-fcf7e5dfc5c2" />

<h2>Carga de la tabla DimCustomers</h2>
<img width="1004" height="484" alt="image" src="https://github.com/user-attachments/assets/7c147f16-3366-488e-8065-0d92fa36c85e" />
<img width="585" height="631" alt="image" src="https://github.com/user-attachments/assets/7c8adbe1-0320-4161-bc14-2111674d2b23" />
<img width="618" height="536" alt="image" src="https://github.com/user-attachments/assets/52a6abf1-e66e-4279-b9ec-030b8d2a753b" />

<h2>Carga de la tabla DimDates</h2>
<img width="950" height="436" alt="image" src="https://github.com/user-attachments/assets/50855c59-c918-4b2a-97b3-5115af6a0819" />
<img width="621" height="667" alt="image" src="https://github.com/user-attachments/assets/23f2fdec-34e2-4a14-bc6d-c9be47c79ab2" />
<img width="975" height="583" alt="image" src="https://github.com/user-attachments/assets/c6f8eb86-3dcf-4c11-af3e-d6e81463742d" />

<h2>Carga de la tabla FactOrders</h2>
<img width="1066" height="495" alt="image" src="https://github.com/user-attachments/assets/128b8dc9-b52a-499c-9604-dd07abb250d1" />
<img width="617" height="658" alt="image" src="https://github.com/user-attachments/assets/82c02ffd-6e9d-4e8d-83fe-162fc94ae4be" />
<img width="697" height="506" alt="image" src="https://github.com/user-attachments/assets/154df3ef-9307-45bf-a63a-169dc37992e0" />

<h2>Carga de la tabla DimCategory</h2>
<img width="975" height="426" alt="image" src="https://github.com/user-attachments/assets/28455d78-a35b-498b-9755-4bbab827157a" />
<img width="677" height="464" alt="image" src="https://github.com/user-attachments/assets/b0438fc7-3640-45ac-8bbc-a48d6b4cf79a" />
<img width="975" height="544" alt="image" src="https://github.com/user-attachments/assets/c0acdac1-9009-4671-b2dc-8de6debde72d" />

<h2>Carga de la tabla DimProducts</h2>
<img width="856" height="458" alt="image" src="https://github.com/user-attachments/assets/53cd6dfb-294e-435f-8446-26b983359554" />
<img width="590" height="487" alt="image" src="https://github.com/user-attachments/assets/b755056b-4f51-48b1-ba13-9f80f1249d8b" />
<img width="1060" height="521" alt="image" src="https://github.com/user-attachments/assets/8ca34b9d-02f6-4db8-bfef-26ce0fe81a85" />

<h2>Carga de la tabla FactOrder_Details</h2>
<img width="848" height="426" alt="image" src="https://github.com/user-attachments/assets/b687b318-9471-4677-b3c5-757ed5d19d91" />
<img width="816" height="654" alt="image" src="https://github.com/user-attachments/assets/dc439e2f-9fe0-497d-8499-9071dbf4dcb1" />
<img width="925" height="800" alt="image" src="https://github.com/user-attachments/assets/ba116880-6bdd-4203-b648-51265615d782" />


