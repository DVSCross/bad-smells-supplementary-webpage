### Supplementary Webpage ###

### Dataset Download

**Class Level**
- [God Class](https://drive.google.com/open?id=1VRkqyqjKG98COWuhaed-_40vkBDKD8y0)
- [Refused Parent Bequest](https://drive.google.com/open?id=1m4wEa5WuzeG1t7LV0u8qxtRKRwS7ivKc)

**Method Level**
- [Long Method](https://drive.google.com/open?id=1izd9i_D0KHO-PNvQJ6k17Qc-jMufgJra)
- [Feature Envy](https://drive.google.com/open?id=18Xu1UNyrwkH4C6fqQ8iOap_2gPQgZyp1)

### List of Systems
- apache-commons-lang
- apache-commons-codec
- apache-commons-io
- apache-commons-logging
- apache-lucene
- checkstyle
- hadoop
- hibernate
- htmlunit
- jasperreports
- jfreechart
- jhotdraw
- jmeter
- quartz
- spring-framework
- squirrelsql
- struts
- tapestry
- tomcat
- weka

### List of Metrics

#### Class Level
- Couple Between Objects (CBO)
- McCabe Cyclomatic Complexity (CYC)
- Data Abstraction Coupling (DAC)
- Depth of Inheritance Tree (DIT)
- Improved Lack of Cohesion in Methods (ILCOM)
- Lack of Cohesion in Methods (LCOM)
- Locality of Data (LD)
- Length of Class Names (LEN)
- Lines of Code (LOC)
- Lack of Documentation (LOD)
- Message Passing Coupling (MPC)
- Number of Attributes and Methods (NAM)
- Number of Children (NOC)
- Number of Local Methods (NOM)
- Response For a Class (RFC)
- Tight Class Cohesion (TCC)
- Weighted Method Count (WMC)

#### Method Level
- Couple Between Objects (CBO)
- Highest Number of Nested Blocks (maxNestedBlocks)
- Lines of Code (LOC)
- Number of Unique Words (uniqueWordsQty)
- Quantity of Assignments (assignmentsQty)
- Quantity of Comparisons (comparisonsQty)
- Quantity of Loops (loopQty)
- Quantity of Parenthesized Expressions (parenExpsQty)
- Quantity of Variables (variables)
- Response For a Class (RFC)
- Size of Parameter List (parameters)
- Method Start Line(startLine)
- Weighted Method Count (WMC)


### Manual Validation Questions
*The answer after the question defines which answer indicates the presence of Bad Smell.*

**God Class**
- Does the class have more than one responsibility? *Yes*
- Does the class have functionality that would fit better into other classes? *Yes*
- Would splitting up the class improve the overall design? *Yes*

*Reference: Building Empirical Support for Automated Code Smell Detection. Jan Schumacher et al.*

**Refused Parent Bequest**
- Does the class use only a little of parent's behaviour? *Yes*
- Does the parent class provide more than a few protected members? *Yes*
- Does the class is too small/simple? *No*

*Reference: Object-Oriented Metrics in practice. Michele Lanza, Radu Marinescu. (Book)*

**Long Method**
- Does the method have many conditional branches? *Yes*
- Does the method is excessively large? *Yes*
- Does the method use many variables? *Yes*

*Reference: Object-Oriented Metrics in practice. Michele Lanza, Radu Marinescu. (Book)*

**Feature Envy**
- Does the method use directly more than a few attributes of other classes? *Yes*
- Does the method use far more attributes from other classes than its own? *Yes*
- Do the used "foreign" attributes belong to very few other classes? *Yes*

*Reference: Object-Oriented Metrics in practice. Michele Lanza, Radu Marinescu. (Book)*

### Related Work 
[Comparison Summary](https://drive.google.com/file/d/1uteFL36uRJqBnnANA0H1Hbt7lrXayp40/view?usp=sharing)
