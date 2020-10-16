1. LCFCRData（There are three compressed files in this folder）

   (1) Rk-1_Data: review/issue/commit of Rk-1 and changeLog of Rk+1

   (2) commit_fixed_file: fixed files for each commit 

   (3) experience_data: detailed data throughout the experiment(includes: javaFile、javaASTFile、review、commitData、richCode、clusterAndIssue、richFeedback、result)

   

2. LCFCRCode

   (1)richCode.py: get richCode for each app
   
   (2)richFeedbackDic.py: get richFeedback for each app
   
   (3)similarityComputer.py: use richCode and richFeedback to computer similarity, then get the file similarity.txt
   
   (4)recommend.py: use similarity.txt to form a recommendation list



3. bertLabelData
