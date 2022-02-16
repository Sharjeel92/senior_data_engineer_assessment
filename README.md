# senior_data_engineer_assessment


The following questions will be used to assess your ability to design, architect maintainable and scalable code.   Please fork this repo.

Submit everything needed to execute and validate your solutions for each of your answers.

Writing comprehesive tests are critical when submitting your solution.

<ol>1.  SQL</ol>

<ul>In this respository is a subset of clinician data.  This data contains Hold slots within a given clinicians calendar.  </br> Using the below details - Write a query that expands the [hold_block_rules.csv](https://github.com/bridgetlandis/senior_data_engineer_assessment/blob/main/hold_block_rules.csv)
 holds and blocks for day.</br>  Things you will need to know: 

<ul> 1.  Rule Type Definitions: 
  <ul>
    0: occuring once</br>
    1: occuring everyday
  </ul>
</ul>
<ul> 2.  Column Details:
  <ul>
    rule_id: distinct id for each rule</br>
    provider_id: distinct id for each provider</br>
    start_date_time: start date and time for given rule</br>
    end_date_time: end date and time for given rule</br>
    rule_text: rule in text format </br>
    availability_type: if the rule is a Hold or Block
  </ul>
</ul>
<ul>3. Availability Type:
  <ul> 
    1 - hold</br>
    2 - block
  </ul>
</ul>
</ul>

<ul>Note:  You must create your own Database and tables for this.  Please provide all scripts so that the evaluator can execute and validate your solutions.</ul></ul> 


<ol>2.  PySpark </ol>

<ul>Leveraging python (no direct SQL please) import the two csv files in the repo.</br>
		<ul>a. Create a staged version of the data</ul>
		<ul>b. Create a clinician mart</ul>
		<ul>c. Only store clinical titles </ul>
		<ul>d. Store only number after the "-"</ul>
		<ul>e. Create - Unique NPIs only</ul>
    <ul>f. Write tests.</ul>
</ul>
