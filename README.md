# QWatch Pro Reverse Engineering & Testing

🧭 This beginner-level QA project explores how to reverse engineer and test an Android smartwatch companion app — QWatch Pro — focusing on customizing watch face presets and validating app stability post-modification.

---

## 🧪 What I Did

- Decompiled the original `QWatch Pro.apk` using **ApkTool**
- Explored the resource structure (`res/`, `assets/`, `drawable/`, `layout/`)
- Identified and replaced preset watch face images with custom images
- Edited XML layout file `fragment_watch_face_diy.xml` to bind new assets
- Rebuilt and signed the APK for safe installation
- Installed and tested on emulator/device for behavior, stability, and UI
- Wrote manual test cases to validate functionality

---

## 🛠 Tools Used

- ApkTool
- Android Debug Bridge (ADB)
- Visual Studio Code
- Java (APK signing)
- XML, Smali
- Real Watch & Emulator for testing

---

## ✅ Manual Test Cases

| ID     | Scenario                                 | Expected Result                         |
|--------|------------------------------------------|------------------------------------------|
| QWT001 | Decompile APK                            | Successfully decompiled                  |
| QWT003 | Replace drawable images                  | Custom wallpapers applied                |
| QWT005 | Rebuild APK                              | APK builds without errors                |
| QWT007 | Install and open app                     | App installs and runs                    |
| QWT008 | Preview custom watchface                 | Custom image visible in UI               |
| QWT009 | Test all major features                  | All original features work post-mod      |
| QWT010 | Stability check post-mod                 | No crashes after 10+ mins                |
| QWT011 | Image scaling and alignment              | Image fits correctly                     |
| QWT013 | Settings persistence                     | Custom face remains after app restart    |

👉 Full list of 15 test cases available in `QWatch_Test_Cases.xlsx`

---

## 📝 What I Learned

- Android APK structure and layout logic  
- XML-based layout customization  
- Drawable resource referencing  
- Basic smali navigation and asset binding  
- How to test manually after modding an app

---

## 🚧 Notes

- This project is for learning & demonstration purposes only.
- Do not redistribute modified APKs publicly.
- Compatible with QWatch Pro version used at the time of extraction.


## Note: cant provide actual code of the project, as it will cause the legal problem for the actual application of the BRAND.  :)
