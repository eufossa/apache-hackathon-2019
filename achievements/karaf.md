# Apache Karaf achievements

Apache Karaf has been represented by one committer and initially planned no training session. After welcome and brief description of project and ecosystem audience showed an interest in small session about web services, software integration and use of projects which relates to Apache Karaf such Apache ActiveMQ, Apache Camel and Apache CXF.

During introduction project representative and couple of EU organisations employees were discussing traceability, monitoring in context of software integration. First day was almost entirely occupied by this activity. Second day was starting from a small project with one of the participants interested in ETL tools which covered getting a first basic Apache Camel integration project which showed how project is structured, configured and run under Apache Karaf.

Saturday's evening was [first code achievement](https://github.com/splatch/plc4x/commit/d8997e1cd22ce548e4961bc10509fdaf05a906a8) related to Apache PLC4X project which provided incomplete Apache Karaf integration. Commit during this day included removal of old codebase, verification of feature set and basic unit tests which check installation at runtime.

Sunday afternoon resulted in three more commits - [first one](https://github.com/splatch/plc4x/commit/dacaf245ed9760a746efb3989e1b24d735650045) adjusted unit tests and missing source file headers (containing license information) and prepared plc4x-api feature together with simple Apache Karaf distribution which embedded plc4x. This was required for further evolution of tests.

[Second commit](https://github.com/splatch/plc4x/commit/5ce379cf8d2f5dc91fdfb6d8a8e2c0531906e69f) from Sunday introduced OSGi version of PlcDriverManager which allows to dynamically register, unregister, lookup drivers at runtime.

[Third commit](https://github.com/splatch/plc4x/commit/dfa98e2ee939d66c2e4d9fcf86d7abfb8c54ef66) fixed issues with test execution, again adjusted source file headers and added some more comments to improve overall maintainability.

Commits will be included in Apache PLC4X project. Additional discussion with project team will take place on [Apache mailing lists](http://plc4x.apache.org/mailing-lists.html) ([public archive of development mailing list](http://mail-archives.apache.org/mod_mbox/plc4x-dev/), [May 2019 archive for development mailing list](http://mail-archives.apache.org/mod_mbox/plc4x-dev/201905.mbox/browser)).

## Overall achievements

* Project members present on site: 1
* External community members attracted: 3+ (2 within EU institutions, one foreign). Minor exchanges lead to further promotion of other OSS projects which could be useful within EU installations.
* Total commits: 4 (all towards Apache PLC4X - linked above)
* Documentation: A person who has been newly introduced to project during training, declared interest in reviewing documentation from newcomer point of view and help making it easier to pick up for people in early stage of interest.
* Community benefits: Exposure to EU institution members proved that some of technics which are common in use in Open Source software integration may help in supporting software installations within public organisations. Further discussions about "internet scale" solutions such containerisation, orchestration briefly touched new challenges within digital transformation for public administration.
* Commits and code provided during hackathon represent value added for both Apache Karaf as it might get a chance to become platform of choice for PLC4X project. Both project can form complete solution together. Provided OSGi (lower level) patches allow use of PLC4X within various IoT/IIoT gateways (Java/OSGi enabled). These can be based on Open Source as well as proprietary software.
