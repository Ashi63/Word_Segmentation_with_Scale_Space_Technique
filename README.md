# Word_Segmentation_with_Scale_Space_Technique
Implementation of scale space technique for word segmentation. Even though the paper is from 1999, the method still achives good results, is fast, and has a simple implementation. The algorithm takes an image containing words as input and outputs the detected words. Optionally, the words are sorted according to reading order (top to bottom, left to right).

## Installlation
- Go to the root level of the repository.
- Execute pip install .
- Go to tests/ and execute pytest to check if installation worked.

## Usage
This example loads an image of a text line, prepares it for the detector (1), detects words (2), sorts them (3), and finakky shows the cropped words (4).

