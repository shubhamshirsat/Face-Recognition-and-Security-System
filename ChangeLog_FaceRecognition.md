## 21 Feb 2019
1. bug fix: found on 21 Feb 2019
    - description: the home door would open for unauthorized people if an authorized person had come before him
    - solution: once the image is used for recognition, it will be deleted. Hence the same image can not be reused in future.
2. bug fix: found on 19 Feb 2019
    - description: if "face_recognition_module.py" was not able to find a face in the image taken, then it was throwing an IndexOutOfBound error
    - solution: if face is not found, then it is not used for comparison
3. change: when name of the person was being extracted from the image name by removing 7 characters from the end of the image name.
    - now, the name is extracted dynamically by using "\_" as a separator


## 17 Feb 2019
1. change: indentation has been standardized to spaces instead of tabs
2. change: "main.py" is split into "main_door.py" and "main_add_new_face.py"
    - "main.py" will be deleted in future
3. new: user name is taken when a photo is going to be added to known_people list

## 14 Feb 2019
1. new: combined the "cam.py" and "face_recognition_module.py" module using "main.py"

## 13 Feb 2019
1. new: python module to take pictures and store it in the required folder which is used by "face_recognition_module.py"

## 11 Feb 2019
1. new: python module for face recognition and comparison using the face_recognition library
