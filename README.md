# LogAnalyzer_new

Add /jars/timerloganalyzer_2.12-1.0.jar to Module setting of project (Right Click the project --> Open Module Setting --> Modules --> add timerloganalyzer_2.12-1.0.jar)


For building the class for new project or any change in existing .scala,,use LogAnalyzer_new one and when .class is created then use log-analyzer_ifUHaveClassFile.zip or use bat file in LogAnalyzer_new one


 // val patt = """\[\d{1,2}\/\d{2}\/\d{2} \d{1,2}:\d{2}:\d{2}:\d{3} GMT\] \w+ \w+.*O (\d{4}-\d{2}-\d{2} \d\d:\d\d:\d\d,\d{3}):TIMER  :(.+?): (.+?) - (Begin|End).+?: (\w+).*""".r
can also be used for Joann as few app server logs doesnot work with old .class

