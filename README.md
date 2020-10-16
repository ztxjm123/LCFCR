1. LCFCRData（There are three compressed files in this folder）

   (1) app_source_code

   (2) original-sql: sql of review/issue/commit

   (3) commit_fixed_file: fixed files for each commit 

   (4)experience_doing_data: detailed data throughout the experiment(includes: javaFile、javaASTFile、commitData、richCode、clusterAndIssue、richFeedback、result)

   

2. LCFCRCode

   (1)richCode.py: get richCode for each app
   
   (2)richFeedbackDic.py: get richFeedback for each app
   
   (3)similarityComputer.py: use richCode and richFeedback to computer similarity, then get the file similarity.txt
   
   (4)recommend.py: use similarity.txt to form a recommendation list



3. bertLabelData