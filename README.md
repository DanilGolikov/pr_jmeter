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
