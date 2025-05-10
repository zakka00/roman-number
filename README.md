

### Build & Coverage Report
Log finale Maven (ultime righe):
```
[INFO] --- jacoco:0.8.8:report (default-cli) @ roman-number ---
[INFO] Loading execution data file /home/runner/work/roman-number/roman-number/target/jacoco.exec
[INFO] Analyzed bundle 'roman-number' with 3 classes
[INFO] 
[INFO] --- checkstyle:3.1.2:checkstyle (default-cli) @ roman-number ---
[WARNING] Old version of checkstyle detected. Consider updating to >= v8.30
[WARNING] For more information see: https://maven.apache.org/plugins/maven-checkstyle-plugin/examples/upgrading-checkstyle.html
[INFO] Starting audit...
Audit done.
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  7.454 s
[INFO] Finished at: 2025-05-10T00:02:23Z
[INFO] ------------------------------------------------------------------------
```
```csv
GROUP,PACKAGE,CLASS,INSTRUCTION_MISSED,INSTRUCTION_COVERED,BRANCH_MISSED,BRANCH_COVERED,LINE_MISSED,LINE_COVERED,COMPLEXITY_MISSED,COMPLEXITY_COVERED,METHOD_MISSED,METHOD_COVERED
roman-number,it.unipd.mtss,App,7,0,0,0,3,0,2,0,2,0
roman-number,it.unipd.mtss,IntegerToRoman,5,0,0,0,2,0,2,0,2,0
roman-number,it.unipd.mtss,RomanPrinter,9,0,0,0,3,0,3,0,3,0
```
Violazioni Checkstyle:
Errori rilevati: 0

A

