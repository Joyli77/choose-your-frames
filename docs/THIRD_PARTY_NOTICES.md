# Third-party notices

This project uses `@mediapipe/tasks-vision` and the MediaPipe Face Landmarker
model for on-device facial landmark detection.

- Project: Google AI Edge MediaPipe
- License: Apache License 2.0
- Source: https://github.com/google-ai-edge/mediapipe
- Documentation: https://developers.google.com/edge/mediapipe/solutions/vision/face_landmarker/web_js

MediaPipe is used only to locate facial landmarks. This application does not
use those landmarks for identity recognition.

This project also uses `tesseract.js`, Tesseract OCR WebAssembly components,
and the Simplified Chinese language data for on-device document recognition.

- Project: Tesseract.js
- License: Apache License 2.0
- Source: https://github.com/naptha/tesseract.js
- OCR engine: https://github.com/tesseract-ocr/tesseract
- Language data: https://github.com/tesseract-ocr/tessdata

The OCR worker, engine, and language data are served from this application.
Customer document images are processed in the browser and are not sent to an
OCR service by this prototype.

This project also uses `read-excel-file` to read `.xlsx` customer lists in the
browser.

- Project: read-excel-file
- Version: 9.3.4
- License: MIT
- Source: https://gitlab.com/catamphetamine/read-excel-file

Excel files are parsed on the current device. The original workbook is not
uploaded to an external spreadsheet service.
