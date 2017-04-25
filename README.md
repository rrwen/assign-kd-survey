
# A Brief Survey on Event Detection Methods for Geo-social Media Data

Richard Wen  
rwen@ryerson.ca      
April 24, 2017  
Assignment for Knowledge Discovery Course  
Instructed by Dr. Cherie Ding  

- [PDF](https://github.com/rrwen/assign-kd-survey/blob/master/pdf/index.pdf)

## Abstract

In this survey, 5 research papers from 2013 to 2017 were selected from the ACM digital library by using automated and manual criteria. These 5 papers were summarized to present commonly used raw data structures and processed data structures for geo-social media event detection. It was found that frequency-based event detection methods in the selected papers were commonly implemented with statistical measures to determine irregular frequencies in geo-social media data. These irregular location referenced frequencies were determined as events. In order for event detection methods to take advantage of geo-social media data, algorithms must ideally be efficient, scalable, and adaptable. For future work, incorporating video and sound data, integrating web-based knowledge resources, standardizing data structures, and working towards event prediction were suggested to improve and advance event detection methods for geo-social media data.

## References

- Hamed Abdelhaq and Michael Gertz. 2014. On the Locality of Keywords in Twitter Streams. In Proceedings of the 5th ACM SIGSPATIAL International Workshop on GeoStreaming (IWGS ’14). ACM, New York, NY, USA, 12–20. https://doi.org/10.1145/2676552.2676554
- Erich Schubert, Michael Weiler, and Hans-Peter Kriegel. 2016. SPOTHOT: Scalable Detection of Geo-spatial Events in Large Textual Streams. In Proceedings of the 28th International Conference on Scientific and Statistical Database Management (SSDBM ’16). ACM, New York, NY, USA, Article 8, 12 pages. https://doi.org/10.1145/2949689.2949699
- Motohiro Shirai, Masaharu Hirota, and Hiroshi Ishikawa. 2013. A Method of Area of Interest and Shooting Spot Detection Using Geo-tagged Photographs. In Proceedings of The First ACM SIGSPATIAL International Workshop on Computational Models of Place (COMP ’13). ACM, New York, NY, USA, Article 34, 8 pages. https://doi.org/10.1145/ 2534848.2534854
- Yuhui Wang and Mohan S. Kankanhalli. 2015. Tweeting Cameras for Event Detection. In Proceedings of the 24th International Conference on World Wide Web (WWW ’15). International World Wide Web Conferences Steering Committee, Republic and Canton of Geneva, Switzerland, 1231–1241. https://doi.org/10.1145/2736277.2741634
- FeiWu, Zhenhui Li,Wang-Chien Lee, HongjianWang, and Zhuojie Huang. 2015. Semantic Annotation of Mobility Data Using Social Media. In Proceedings of the 24th International Conference on World Wide Web (WWW ’15). International World Wide Web Conferences Steering Committee, Republic and Canton of Geneva, Switzerland, 1253–1263. https://doi.org/10.1145/2736277.2741675

## Developer Notes

1. Install [Text Live]() or [Miktex]()
2. Generate **pdf/index.pdf**

```
latex index.tex -output-directory=log -interaction=nonstopmode
bibtex log/index.aux
latex index.tex -output-directory=log -interaction=nonstopmode
pdflatex index.tex -output-directory=pdf -aux-directory=log -interaction=nonstopmode
```

If regenerating the PDF:

```
pdflatex index.tex -output-directory=pdf -aux-directory=log -interaction=nonstopmode
```
