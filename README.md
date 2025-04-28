# MNIST Digit Classification using Logistic Regression
(تصنيف أرقام MNIST باستخدام الانحدار اللوجستي)

## Short Description (وصف مختصر)

This project demonstrates the classification of handwritten digits (0-9) from the MNIST dataset using a simple Logistic Regression model implemented with scikit-learn.
(يوضح هذا المشروع تصنيف الأرقام المكتوبة بخط اليد (0-9) من مجموعة بيانات MNIST باستخدام نموذج انحدار لوجستي بسيط تم تنفيذه باستخدام scikit-learn.)

## Project Overview (نظرة عامة على المشروع)

The notebook `moaz amr.ipynb` performs the following steps:
(يقوم ملف `moaz amr.ipynb` بالخطوات التالية:)

1.  **Load Data:** Loads the MNIST dataset using `keras.datasets.mnist`.
    (تحميل البيانات: تحميل مجموعة بيانات MNIST باستخدام `keras.datasets.mnist`.)
2.  **Preprocessing:**
    (المعالجة المسبقة:)
    *   Reshapes the 28x28 pixel images into 784-element vectors.
        (إعادة تشكيل الصور بحجم 28x28 بكسل إلى متجهات مكونة من 784 عنصرًا.)
    *   Normalizes the pixel values to be between 0 and 1 by dividing by 255.
        (تطبيع قيم البكسل لتكون بين 0 و 1 عن طريق القسمة على 255.)
3.  **Model Training:** Trains a `LogisticRegression` model from `sklearn.linear_model` on the training data.
    (تدريب النموذج: تدريب نموذج `LogisticRegression` من `sklearn.linear_model` على بيانات التدريب.)
4.  **Evaluation:** Predicts labels for the test set and calculates the accuracy score using `sklearn.metrics.accuracy_score`.
    (التقييم: التنبؤ بالتصنيفات لمجموعة الاختبار وحساب درجة الدقة باستخدام `sklearn.metrics.accuracy_score`.)

## Dataset (مجموعة البيانات)

*   **MNIST:** A large database of handwritten digits commonly used for training various image processing systems.
    (MNIST: قاعدة بيانات كبيرة للأرقام المكتوبة بخط اليد تُستخدم بشكل شائع لتدريب أنظمة معالجة الصور المختلفة.)

## Model Used (النموذج المستخدم)

*   **Logistic Regression:** A linear model for binary classification problems, adapted here for multi-class classification (digits 0-9).
    (الانحدار اللوجستي: نموذج خطي لمشاكل التصنيف الثنائي، تم تكييفه هنا للتصنيف متعدد الفئات (الأرقام 0-9).)

## Requirements (المتطلبات)

*   Python 3
*   NumPy
*   Pandas
*   Scikit-learn
*   TensorFlow/Keras (primarily for dataset loading)
    (بشكل أساسي لتحميل مجموعة البيانات)
*   Matplotlib (for visualization)
    (للتصور البياني)

## How to Run (كيفية التشغيل)

1.  Ensure you have the required libraries installed (`pip install numpy pandas scikit-learn tensorflow matplotlib`).
    (تأكد من تثبيت المكتبات المطلوبة.)
2.  Run the Jupyter Notebook `moaz amr.ipynb`.
    (قم بتشغيل ملف Jupyter Notebook `moaz amr.ipynb`.)
