# Lab5_202001116
this repo contains readme file for lab 5 of software engineering course (IT314) of DAIICT



# Subject: Software Engineering
# Subject code: IT314

# Lab 5
Date of submission:15/3/23
Due date of submission:15/3/23

# Name: Gaurav Shah

# Topic: Statistical analysis
Project selected for analysis : Face recognition master
Recognize and manipulate faces from Python or from the command line with the world's simplest face recognition library.
Built using dlib's state-of-the-art face recognition built with deep learning. The model has an accuracy of 99.38% on the Labeled Faces in the Wild benchmark.
GitHub Link : https://github.com/ageitgey/face_recognition.git

Tool used for analysis : pylint

# Analysis for code file : setup.py

analysis : 
PS C:\Users\shahg\Downloads\face_recognition-master\face_recognition-master> pylint setup  
************* Module setup  
setup.py:1:0: C0114: Missing module docstring (missing-module-docstring)  
setup.py:6:5: W1514: Using open without explicitly specifying an encoding (unspecified-encoding)  
setup.py:9:5: W1514: Using open without explicitly specifying an encoding (unspecified-encoding)  

------------------------------------------------------------------  
Your code has been rated at 6.25/10 (previous run: 6.25/10, +0.00)  


# Analysis for code file : web_service_example.py

analysis : 
PS C:\Users\shahg\Downloads\face_recognition-master\face_recognition-master\examples> pylint .\web_service_example.py  
************* Module web_service_example  
web_service_example.py:14:0: C0301: Line too long (112/100) (line-too-long)  
web_service_example.py:101:0: C0301: Line too long (104/100) (line-too-long)  
web_service_example.py:1:0: C0114: Missing module docstring (missing-module-docstring)  
web_service_example.py:19:0: E0401: Unable to import 'face_recognition' (import-error)  
web_service_example.py:20:0: E0401: Unable to import 'flask' (import-error)  
web_service_example.py:28:0: C0116: Missing function or method docstring (missing-function-docstring)  
web_service_example.py:34:0: C0116: Missing function or method docstring (missing-function-docstring)  
web_service_example.py:61:0: C0116: Missing function or method docstring (missing-function-docstring)  

-----------------------------------
Your code has been rated at 4.84/10  


# Analysis for code file : benchmark

analysis : 
PS C:\Users\shahg\Downloads\face_recognition-master\face_recognition-master\examples> pylint benchmark  
************* Module benchmark  
benchmark.py:5:0: C0301: Line too long (120/100) (line-too-long)  
benchmark.py:6:0: C0301: Line too long (115/100) (line-too-long)  
benchmark.py:18:0: C0301: Line too long (102/100) (line-too-long)  
benchmark.py:73:0: C0301: Line too long (123/100) (line-too-long)  
benchmark.py:74:0: C0301: Line too long (127/100) (line-too-long)  
benchmark.py:75:0: C0301: Line too long (135/100) (line-too-long)  
benchmark.py:76:0: C0301: Line too long (115/100) (line-too-long)  
benchmark.py:1:0: C0114: Missing module docstring (missing-module-docstring)  
benchmark.py:17:0: C0116: Missing function or method docstring (missing-function-docstring)  
benchmark.py:24:0: C0103: Constant name "setup_locate_faces" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:30:0: C0103: Constant name "test_locate_faces" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:34:0: C0103: Constant name "setup_face_landmarks" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:41:0: C0103: Constant name "test_face_landmarks" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:45:0: C0103: Constant name "setup_encode_face" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:52:0: C0103: Constant name "test_encode_face" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:56:0: C0103: Constant name "setup_end_to_end" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:62:0: C0103: Constant name "test_end_to_end" doesn't conform to UPPER_CASE naming style (invalid-name)  
benchmark.py:71:10: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)  
benchmark.py:73:10: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)  
benchmark.py:74:10: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)  
benchmark.py:75:10: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)  
benchmark.py:76:10: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)  

-----------------------------------
Your code has been rated at 1.20/10


# Analysis for code file : blink_detection.py

analysis : 
PS C:\Users\shahg\Downloads\face_recognition-master\face_recognition-master\examples> pylint .\blink_detection.py  
************* Module blink_detection  
blink_detection.py:4:0: C0301: Line too long (166/100) (line-too-long)  
blink_detection.py:9:0: C0301: Line too long (110/100) (line-too-long)  
blink_detection.py:10:0: C0301: Line too long (106/100) (line-too-long)  
blink_detection.py:11:0: C0301: Line too long (109/100) (line-too-long)  
blink_detection.py:43:0: C0303: Trailing whitespace (trailing-whitespace)  
blink_detection.py:65:0: C0325: Unnecessary parens after 'if' keyword (superfluous-parens)  
blink_detection.py:71:0: C0325: Unnecessary parens after 'if' keyword (superfluous-parens)  
blink_detection.py:73:0: C0325: Unnecessary parens after 'while' keyword (superfluous-parens)  
blink_detection.py:76:68: C0303: Trailing whitespace (trailing-whitespace)  
blink_detection.py:90:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)  
blink_detection.py:91:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)  
blink_detection.py:92:0: C0303: Trailing whitespace (trailing-whitespace)  
blink_detection.py:95:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)  
blink_detection.py:96:0: C0303: Trailing whitespace (trailing-whitespace)  
blink_detection.py:98:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)  
blink_detection.py:99:0: C0303: Trailing whitespace (trailing-whitespace)  
blink_detection.py:101:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)  
blink_detection.py:105:0: C0305: Trailing newlines (trailing-newlines)  
blink_detection.py:1:0: C0114: Missing module docstring (missing-module-docstring)  
blink_detection.py:14:0: E0401: Unable to import 'face_recognition' (import-error)  
blink_detection.py:15:0: E0401: Unable to import 'cv2' (import-error)  
blink_detection.py:17:0: E0401: Unable to import 'scipy.spatial' (import-error)  
blink_detection.py:21:0: C0116: Missing function or method docstring (missing-function-docstring)  
blink_detection.py:21:0: R0914: Too many local variables (18/15) (too-many-locals)  
blink_detection.py:33:4: R1702: Too many nested blocks (6/5) (too-many-nested-blocks)  
blink_detection.py:25:4: W0612: Unused variable 'ret' (unused-variable)  
blink_detection.py:86:0: C0116: Missing function or method docstring (missing-function-docstring)  
blink_detection.py:90:1: C0103: Variable name "A" doesn't conform to snake_case naming style (invalid-name)  
blink_detection.py:91:1: C0103: Variable name "B" doesn't conform to snake_case naming style (invalid-name)  
blink_detection.py:95:1: C0103: Variable name "C" doesn't conform to snake_case naming style (invalid-name)  
blink_detection.py:16:0: C0411: standard import "import time" should be placed before "import face_recognition" (wrong-import-order)  
blink_detection.py:16:0: W0611: Unused import time (unused-import)  

-----------------------------------
Your code has been rated at 1.54/10


# Analysis for code file : digital_makeup

analysis : 
PS C:\Users\shahg\Downloads\face_recognition-master\face_recognition-master\examples> pylint .\digital_makeup.py  
************* Module digital_makeup  
digital_makeup.py:31:0: C0301: Line too long (102/100) (line-too-long)  
digital_makeup.py:32:0: C0301: Line too long (104/100) (line-too-long)  
digital_makeup.py:1:0: C0114: Missing module docstring (missing-module-docstring)  
digital_makeup.py:1:0: E0401: Unable to import 'PIL' (import-error)  
digital_makeup.py:2:0: E0401: Unable to import 'face_recognition' (import-error)  

-----------------------------------
Your code has been rated at 3.50/10
