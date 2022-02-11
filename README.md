# everything-recognition
Упражнение на чтение кода. Распознавание образов

# run.py
## is_user_wants_quit
return True if user press "q" button

## show_frame(frame)
display content "frame" in specified window

## draw_sqare(frame, color)
draw rectangular over captured object

## get_cascades()
get all detected in the frame persons or their body parts

## main
1. get_cascades.
2. start capturing video from default camera in new window
3. start endless cycle 
4. get captured image
5. draw rectangulars over each detected, using cascade, object 
6. show new frame with rectangulars
7. if user pressed "q" - break cycle, deactivate capturing video and close all windows
