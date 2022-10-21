GanttProject
============
GanttProject is an open-source desktop project scheduling and management tool. It is written in Java/Swing.



## License
GanttProject is distributed under GPLv3


# Sorting things out

## Design Patterns

### Guilherme
- ProxyDocument.java **(Proxy)**
	- Reviewer: ---
- CalendarFactory.java **(Factory)**
	- Reviewer: **Pereira**
- UIFacadeImpl.java **(Facade)**
	- Reviewer: **Lopes**

### Fernandes
- StylesheetFactoryImpl.java **(Abstract Factory)**
	- Reviewer: **Guilherme**
- DependencySceneBuilder.java **(Builder)**
	- Reviewer: **Pereira**
- GanttLookAndFeels.java **(Singleton)**
	- Reviewer: ---

### Lopes
- OffsetBuilderImpl.java **(Builder)**
	- Reviewer: **Guilherme**
- GPcalendarProvider.java **(Singleton)**
	- Reviewer: **Pereira**
- ParserFactory.java **(Factory)**
	- Reviewer: ---

### Martins
- CalendarFactory.java **(Factory)**
	- Reviewer: **Guilherme**
- TreeUIFacade.java **(Facade)**
	- Reviewer: ---
- ReadOnlyProxyDocument.java **(Proxy)**
	- Reviewer: **Lopes**

### Pereira
- MiltonResourceFactory.java **(Factory)**
	- Reviewer: ---
- TaskTreeFacade.kt **(Facade)**
	- Reviewer: ---
- TaskListenerAdapter.kt **(Adapter)**
	- Reviewer: **Lopes**


## Code smells

### Guilherme
- Scalr.java **(Comments)**
	- Reviewer: ---
- DateParser.java **(Large class)**
	- Reviewer: **Pereira**
- DateParser.java **(Shotgun surgery)**
	- Reviewer: **Lopes**

### Fernandes
- AbstractChartImplementation.java **(Comments)**
	- Reviewer: **Guilherme**
- CalendarEditorPanel.java **(Large class)**
	- Reviewer: **Pereira**
- GanttChartController.java **(Shotgun surgery)**
	- Reviewer: ---

### Lopes
- Offset.java **(Long parameter list)**
	- Reviewer: **Guilherme**
- DependencySceneBuilder.java **(Comments)**
	- Reviewer: **Pereira**
- ProjectFileImporter.java **(Large class)**
	- Reviewer: ---

### Martins
- GanttCSVExport.java **(Comments)**
	- Reviewer: **Guilherme**
- GanttCSVExport.java **(Long method)**
	- Reviewer: ---
- GanttProject.java **(Large class)**
	- Reviewer: **Lopes**

### Pereira
- GanttOptions.java **(Long method)**
	- Reviewer: ---
- GPTreeTableBase.java **(Large class)**
	- Reviewer: ---
- GPTreeTableBase.java **(Comments)**
	- Reviewer: **Lopes**
