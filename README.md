# FaultContext-based
Weighted the suspicious statements with the fault propagation context. 
---------------------------------
 Building requirements
  Ubuntu 20.04.4 LTS
  java version "1.8.0_311"
 Steps 
 get the spectra with Gzoltar
 calculate the preliminary ranklist of suspicious statements with SBFL methods (Ochiai or others)
 generate the fault propagation context with the com.module.DataDependenceAnalysisBySBFL
 calsulate the new ranklist of suspicious statements and context by com.module.DataDepenceBetweenClz.java
 calculate the metrics (Top-n, Exam) to evaluate the method with the files in finalmodule
