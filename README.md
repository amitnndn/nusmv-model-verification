<h2>NuSMV Code for Model Checker</h2>
<p><strong>Installing NuSMV on MAC:<br/></strong>
<code>$ brew search nusmv</code><small>Searches for NuSMV module</small><br/>
<code>$ brew install nusmv</code><small>Install the NuSMV module</small><br/>

<strong>Running NuSMV in terminal</strong><br/> 
Steps:<br/>
1. Open the NuSMV interactive terminal <code>$ nusmv -int</code><br/>
2. Run the following commands to read the smv file: <br/>
	<code>read_model -i file_name.smv</code><br/>
	<code>flatten_hierarchy</code><br/>
	<code>encode_variables</code><br/>
3. To verify the model and requirements, use <code>check_ltlspec -p "G { your_expression_here }"</code>

<small>Note: I will add the installation instructions for windows and linux distributions soon with the state diagrams of the models presented in this codebase</small>
