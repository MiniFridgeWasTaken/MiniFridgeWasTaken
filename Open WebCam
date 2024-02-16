import cv2 as cv

cap = cv.VideoCapture(0)

if not cap.IsOpened():
  print("404: Web Cam Not Found")
  break

while True:
  ret, frame = cap.read()
  if not ret:
    print("No Capture Found")
    break

  cv.imshow("Webcam",frame)

  if cv.waitKey(1) == ord("q")
    break


cv.release()
cv.destroyAllWindows()

