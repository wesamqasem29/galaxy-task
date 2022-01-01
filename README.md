picture_path=pickAFile()
picture_location=makePicture(picture_path)
show(picture_location)
def fiftyshades(picture_location):
 for pixel in getPixels(picture_location):
  valueBlue=getBlue(pixel)
  valueRed=getRed(pixel)
  valueGreen=getGreen(pixel)
  setBlue(pixel,valueBlue*2)
  setRed(pixel,valueRed*2)
  setGreen(pixel,valueGreen*2)
 show(picture_location)
fiftyshades(picture_location)
repaint(picture_location)
  
