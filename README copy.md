<h1 align="center">BIOMETRICS</h1>
<h2 align="center">Approaches In Palmprint Recognition</h2>
<div align="center">
  <a href="https://github.com/loi5704/Biometrics">
    GitHub
  </a>
</div>

---

<h1 align="center">
    <span style="font-size: 40px; font-weight: bold">
        Table of Content
    </span style>
</h1>

1. [Mục tiêu](#i)
2. [Cấu trúc thư mục](#ii)
3. [Triển khai code các phương pháp (ngoại trừ phương pháp tiên tiến)](#iii)
4. [Triển khai code phương pháp tiên tiến](#iv)
5. [Tham khảo](#v)


<h1 id="i" style="font-weight: bold">1. Mục tiêu</h1>

Trình bày code triển khai các phương pháp trong nhận diện palmprint:

- Phương pháp line-based
- Phương pháp subspace-based
- Phương pháp local statistical
- Phương pháp global statistical
- Phương pháp coding-based
- Phương pháp tiên tiến

<h1 id="ii" style="font-weight: bold">2. Cấu trúc thư mục</h1>

```python
├── codingBasedCode/ # Phương pháp coding-based
│   ├── funcs.py # Các hàm triển khai phương pháp coding-based
│   ├── codingbased-approaches.ipynb # Notebook chứa code.

├── globalStatisticalBasedCode/ # Phương pháp global statistical
│   ├── funcs.py # Các hàm triển khai phương pháp global statistical
│   ├── globalstatisticalbased-approaches.ipynb # Notebook chứa code.

├── linebasedApproachesCode/ # Phương pháp line-based
│   ├── funcs.py # Các hàm triển khai phương pháp line-based
│   ├── linebased-approaches.ipynb # Notebook chứa code.

├── localStatisticBasedCode/ # Phương pháp local statistical
│   ├── funcs.py # Các hàm triển khai phương pháp local statistical
│   ├── localstatisticbased-approaches.ipynb # Notebook chứa code.

├── subspaceBasedCode/ # Phương pháp subspace-based
│   ├── funcs.py # Các hàm triển khai phương pháp subspace-based
│   ├── subspace-based-approaches.ipynb # Notebook chứa code.

├── trainArcFaceCode/ # Phương pháp tiên tiến
│   ├── trainArcFace.ipynb # Notebook chứa code train mô hình nhận diện theo thông số tác giả.
│   ├── trainArcFaceWithNewPipeLine.ipynb # Notebook chứa code train mô hình nhận diện theo phương pháp bổ sung của nhóm.

```

<h1 id="iii" style="font-weight: bold">3. Triển khai các phương pháp truyền thống </h1> 

Triển khai các phương pháp trên 2 datasets sau:

- [Birjand University Mobile Palmprint Database (BMPD)](https://www.kaggle.com/datasets/mahdieizadpanah/birjand-university-mobile-palmprint-databasebmpd)
- [Sapienza University Mobile Palmprint Database (SMPD)](https://www.kaggle.com/datasets/mahdieizadpanah/sapienza-university-mobile-palmprint-databasesmpd)

Môi trường chạy code: Kaggle notebook <br>
Các link kaggle notebook ứng với từng phương pháp:

- [phương pháp line-based](https://www.kaggle.com/code/tmtrnhelloworld/linebased-approaches)
- [phương pháp subspace-based](https://www.kaggle.com/code/tmtrnhelloworld/subspace-based-approaches)
- [phương pháp local statistical](https://www.kaggle.com/code/tmtrnhelloworld/localstatisticbased-approaches)
- [phương pháp global statistical](https://www.kaggle.com/code/tmtrnhelloworld/globalstatisticalbased-approaches)
- [phương pháp coding-based](https://www.kaggle.com/code/tmtrnhelloworld/codingbased-approaches)

<h1 id="iv" style="font-weight: bold">4. Triển khai các phương pháp tiên tiến</h1> 

Triển khai trên 3 datasets sau:

- [Diff-Palm](https://www.kaggle.com/datasets/loinguyen57/dataset-40000-new)
- [Tongji](https://www.kaggle.com/datasets/loinguyen57/tongji-train)
- [IITD](https://www.kaggle.com/datasets/loinguyen57/iitdv1) 

Môi trường chạy code: Kaggle

- [Đường dẫn chạy trainArcFace.ipynb](https://www.kaggle.com/code/vitliinh/train-arcface)
- [Đường dẫn chạy trainArcFaceWithNewPipeLine.ipynb](https://www.kaggle.com/code/khangphandik/train-arcface)

<h1 id="v" style="font-weight: bold">5. Tham khảo</h1> 

1.  leSamo (Samuel Olekšák). Biometric Identification Using Principal Lines on a Palm. Link github code: https://github.com/leSamo/Principal-Lines-Identification
2.  auduongtansang (Âu Dương Tấn Sang). PalmprintRecognition. Link github code: https://github.com/auduongtansang/PalmprintRecognition
3.  ruofei7 (Ruofei). Palmprint_Recognition. Link github code: https://github.com/ruofei7/Palmprint_Recognition
4.  adailtonjn68 (Adailton Júnior). hu_moments_in_python. Link github code: https://github.com/adailtonjn68/hu_moments_in_python
5.  AdrianUng (Adrian-Stefan Ungureanu). palmprint-feature-extraction-techniques.Link github code: https://github.com/AdrianUng/palmprint-feature-extraction-techniques
