# ANNOTATION_GUIDE.md – Simple Rules for Labeling EUS Pictures

Goal: Everyone uses the SAME words and way to label pictures so AI learns correctly!

### 1. Basic Rules for Every Picture
- Look at the EUS image carefully (still photo from procedure).
- Decide: Is it NORMAL or ABNORMAL?
- If abnormal, what is the main thing you see?
- Use ONLY words from the list below (or add "other" if it doesn't fit).
- If possible, add size (e.g., "cyst 12 mm") or extra notes like "confirmed by biopsy: cancer".
- Save labels in a simple file:
  - For each image, make one line in a .txt or .csv file like:
    image001.jpg | pancreatic cyst | 18 mm | Olympus scope | possible IPMN

### 2. Main Label Categories (Use These!)
Use one main class per image (pick the best one):

Normal / Anatomy Stations (common views in EUS):
- normal pancreas head
- normal pancreas body
- normal pancreas tail
- normal stomach wall
- normal bile duct / CBD
- normal common bile duct stone (if seen but normal)
- normal lymph node station
- normal mediastinum / esophagus station
- other normal station (add description)

Abnormal / Lesions:
- pancreatic cyst (simple / complex)
- pancreatic mass / solid lesion
- pancreatic adenocarcinoma (if known from report)
- pancreatic neuroendocrine tumor
- chronic pancreatitis changes
- bile duct stone / choledocholithiasis
- bile duct stricture / narrowing
- gastric submucosal tumor / GIST
- enlarged lymph node / lymphadenopathy
- liver metastasis (if seen)
- other abnormal (write what it is!)

### 3. How to Mark Location / Extra (Optional but Helpful)
- Add bounding box if you can (draw rectangle around the problem area using free tool like LabelStudio).
- Or just write: "located in pancreas head", "wall of duodenum", etc.
- Equipment: Write brand if known (e.g., "Pentax", "Fujifilm", "Olympus").
- Quality: Good / Okay / Blurry (if blurry, maybe don't include).

### 4. Tools to Use (Free & Easy)
- LabelStudio: Free web tool (install or use online) – great for drawing boxes and picking labels.
- Paint or any photo editor for simple notes.
- Excel or Google Sheets for listing all labels.

### 5. Examples
- Image shows clear round dark area in pancreas → "pancreatic cyst | 15 mm"
- Image shows bright white spot in bile duct → "bile duct stone"
- Normal view looking at pancreas → "normal pancreas body"

Keep it simple at first! We can add more classes later if many people send "other".

Questions? Message me on GitHub!

— Qazi Aamir Suhail
