# FYP_Speech-Processing
2022/2023 FYP Robotic Speech Processing Source Code

To enhance on the RNN text classification model namely "student_model":
  1. Download "Student_Staff Classification.ipynb" and "student_staff.csv".
  2. Google Colab is good enough to train the model as the dataset is very small.
  3. "student_staff.csv" is the current dataset I used to train the model, feel free to enlarge/change the dataset to train a new model.
  4. To run the speech processing module with new model, just the old "student_model" to a new "student_model" will do.
  
If you are using JUNO robot with serial number MA020015, please run these command to run the program:
  1. In first terminal, run: $ roscore
  2. In another new termial, go to the directory that contain the fyp.sh file: $ roscd fyp
  3. Use this command to run the program: $ ./fypsh

If you are using other robot, please follow these steps:
  1. Create a package, can follow the tutorials: http://wiki.ros.org/ROS/Tutorials/CreatingPackage *name the package as "fyp", so that you no need to change the path*
  2. Download all files into the package folder except for "Student_Staff Classification.ipynb" & "student_staff.csv"
  3. Intall requirement.txt: $ pip install -r requirements.txt
  4. Ensure that all the files in the package folder are executable $ chmod +x <filename>.py
  5. In first terminal, run: $ roscore
  6. In another new termial, go to the directory that contain the fyp.sh file: $ roscd fyp
  7. Use this command to run the program: $ ./fypsh
  

