| **Apache NiFi** | Datuen ETL eta bideratzea | `https://localhost:8443/nifi` | `admin` / `adminpassword123` |
| **Kibana** | Bistaratzea eta kontrol-panelak | `http://localhost:5601` | Sarbide librea |
| **Scoring API** | FastAPI Swagger dokumentazioa | `http://localhost:8000/docs` | Sarbide librea |
| **Elasticsearch** | Datu-base dokumentala | `http://localhost:9200` | Sarbide librea |
| **Apache Kafka** | Mezularitza bufferra | `kafka:9092` (Docker barnea) | Barne-erabilera |
---
## 👥 5. Taldeak eta Erakundearen Egitura
Erronka hau erakundeko 5 talde espezializatuk garatzen dute aldi berean:
* 📁 **A-taldea**
* 📁 **B-taldea**
* 📁 **C-taldea**
* 📁 **D-taldea**
* 📁 **E-taldea**
Talde bakoitzak bere GitHub biltegia du esleituta bere aurrerapena, commit-ak eta kodearen bertsio-kudeaketa aurrera eramateko, erakundeko proiektu-taulari (Kanban / Gantt) zuzenean lotuta.
---
## 📊 6. Ebaluazioa eta Entregagarriak
| Atal Ebaluagarria | Pisua | Gakoak |
|---|---|---|
| **1. Fasea — Big Data Pipeline** | **% 35** | Filebeat eraginkorra, NiFi fluxu garbia, ES indexazioa, Kibana 1. panela. |
| **2. Fasea — ML Entrenamendua** | **% 40** | EDA justifikatua, klase-desorekaren kudeaketa, Recall balioak, kode garbia. |
| **3. Fasea — Ekoizpena eta Integrazioa**| **% 20** | FastAPI zerbitzaria, NiFi HTTP integrazioa, alerta-sistema automatizatua. |
| **AI Agenteen Erabilera** | **% 5** | Prompt ingeniaritza eta laguntza-tresnen erabilera kritiko eta arduratsua. |
> 🎁 **Puntu Gehigarriak (+5):** Feature engineering berritzailea, eredu anitzen benchmark-a (RF vs XGBoost), edo APIaren proba automatizatuak (`pytest`).
### 🎤 Amaierako Defentsa (10 minutu taldeko)
1. **Live Demo (2 min):** Simuladorearen datuak Kibanan mugitzen erakutsi.
2. **Data Science Justifikazioa (3 min):** Hartutako erabakiak, metrikak eta Recall-aren garrantzia azaldu.
3. **Alerta-Simulazioa (2 min):** `LARRIA` mailako egoera baten aurrean sistemaren erantzuna bistaratu.
4. **Galderak eta Ingeniaritza-Irizpidea (3 min):** Irakasleen galderei erantzun.
