# FaultContext-based
Weighted the suspicious statements with the fault propagation context. 
---------------------------------
 # Building requirements  
  Ubuntu 20.04.4 LTS  
  java version "1.8.0_311"  
 # Steps   
 1. Getting the spectra with Gzoltar  
 2. Calculating the preliminary ranklist of suspicious statements with SBFL methods (Ochiai or others)  
 3. Generating the fault propagation context with the com.module.DataDependenceAnalysisBySBFL  
 4. Calsulating the new ranklist of suspicious statements and context by com.module.DataDepenceBetweenClz.java  
 5. Getting the metrics (Top-n, Exam) to evaluate the method with the files in finalmodule    
# Gzoltar   
https://github.com/GZoltar/gzoltar  
