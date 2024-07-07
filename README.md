# Smart-Attendance-System-Using-Face-Recognition
Overview
The Smart Attendance System Using Face
Recognition is a software application that automates
attendance-taking using facial recognition
technology. It eliminates the need for manual
attendance-taking, which is time-consuming and
prone to errors. This system enables the recognition
of a person's identity using a camera and compares
it with the database to record attendance

We are building a Smart Attendance System Using
Face Recognition that can automatically take
attendance using facial recognition technology. The
system will use a camera to capture the face of each
person and match it with the database to identify
them. The system will store attendance records for
each person in an Excel file and generates a report

PROPOSED SYSTEM

Dataset Creation
Face Detection

Face detection algorithms work by
detecting facial features such as eyes,
nose, mouth, and their spatial
relationships within an image.
accurately detecting faces, systems
can perform subsequent tasks like
facial recognition, emotion analysis, and
age
Face Recognition

Prepare Training Data: Collect student
face images, assign labels, and
preprocess the data.
Train KNN Model: Feed the labeled data
into the KNN algorithm to learn
associations between faces and labels.
Prediction: When presented with a new
face image, the trained model predicts
the label corresponding to the nearest
neighbor in the training data, identifying
the student.

Attendance Updation

After the face recognition process,
recognized faces are marked as
present in the Excel sheet, while
unrecognized faces are marked as
absent. The system then adds the date
and time alongside the identified
person's name to record attendance.
Finally, it provides verbal confirmation,
announcing the attendance status
aloud.

Evaluation Metrics

Accuracy: An accuracy of 1 means that your classifier correctly classified all samples
in the dataset. There are no misclassifications.
Accuracy: (TP + TN)/ (TP + FN + TN + FP) = 1.0
Precision: A precision of 1 means that all positive predictions made by the classifier
were correct. There are no false positive predictions.
Precision: TP/ (FP + TP) = 1.0
Recall: A recall of 1 means that the classifier correctly identified all positive samples in the
dataset. There are no false negative predictions.
Recall: TP / (TP + FN) = 1.0
F1 Score: The F1 score is the harmonic mean of precision and recall. A value of 1 indicates perfect
balance between precision and recall, meaning there are no false positives or false negatives.
F1 Score: 2 * Precision * Recall / (Precision + Recall) = 1.0



Conclusion

In conclusion, the Smart Attendance Management
System utilizing Face Recognition offers an innovative
and efficient solution for attendance tracking in
institutions. It eliminates manual processes, reducing
errors and saving time. With a user-friendly interface
and live video streams, it promises to revolutionize
attendance management, enhancing efficiency and
accuracy across various institutions.
