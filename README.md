# pr6312_jmeter
Huge thanks to [@KingRabbid](https://github.com/KingRabbid) for adding the functionality and a bunch of new themes.

These changes add a lot of new themes for JMeter.
The changes were extracted and compiled for JMeter 5.6.3 from pull request #6312 in the official JMeter repository (https://github.com/apache/jmeter/pull/6312).
All .class files need to be placed in %jmeter%/lib/ext/ApacheJMeter_core.jar (the .jar file can be opened with 7z or WinRar).
Additionally, the files **flatlaf-3.4.1.jar** and **flatlaf-intellij-themes-3.4.1.jar** need to be placed in %jmeter%/lib.
Below are the full replacement paths for the .class files:

### ApacheJMeter_core.jar\org\apache\jmeter
- SplashScreen.class

### ApacheJMeter_core.jar\org\apache\jmeter\gui
- LoggerPanel.class
- MainFrame.class
- MainFrame$1.class
- MainFrame$WindowHappenings.class
- MainFrame$QuickComponent.class
- MainFrame$ErrorsAndFatalsCounterLogTarget.class

### ApacheJMeter_core.jar\org\apache\jmeter\gui\action
- LookAndFeelCommand.class
- LookAndFeelCommand$MenuItem.class

### ApacheJMeter_core.jar\org\apache\jmeter\gui\util
- JMeterMenuBar.class
- JMeterMenuBar$LangMenuHelper.class
- JSyntaxTextArea.class
- JSyntaxTextArea$1.class

New fields for theme configuration have also appeared in jmeter.properties. It is not mandatory to insert them.
![image](https://github.com/user-attachments/assets/f38a068c-019e-4e14-a858-40779aa777b2)
![image](https://github.com/user-attachments/assets/b0fb224c-95f6-451b-976e-37486707e0f6)
![image](https://github.com/user-attachments/assets/5aae8adc-1a02-441b-b00b-a07b69c55dec)
![image](https://github.com/user-attachments/assets/dec9d2ca-4166-4d04-b0bf-f9fccb26d78e)
![image](https://github.com/user-attachments/assets/8f259a6d-0c6f-4a1a-a6eb-4dac33ac3a7e)






