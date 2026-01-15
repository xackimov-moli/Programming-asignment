## Online Shop Flowchart

flowchart TD
    A[Start] --> B[Menu]

    B --> C[Mahsulotlarni korish]
    B --> D[Mahsulotlarni qidirish]
    B --> E[Savat]
    B --> F[Aksiyalar va Azolik]
    B --> G[Qollab quvvatlash]
    B --> Z[Chiqish]

    D --> D1[Mahsulot nomini yozing]
    D1 --> B

    C --> K[Kategoriyalar]
    K --> K1[Oshxona texnikasi]
    K --> K2[Tozalash uskunalari]
    K --> K3[Isitish va sovitish]
    K --> K4[Shaxsiy parvarish]
    K --> K5[Aqlli uy texnikasi]
    K --> B

    E --> E1{Savat boshmi}
    E1 -->|Ha| E2[Savatcha bosh]
    E2 --> B
    E1 -->|Yoq| E3[Mahsulotlar royxati]

    E3 --> E4{Buyurtma berish}
    E4 -->|Yoq| B
    E4 -->|Ha| E5[Ism Telefon Manzil]

    E5 --> Y{Yetkazish turi}
    Y --> Y1[Manzilga yetkazish]
    Y --> Y2[Dokondan olib ketish]

    Y1 --> F1[Buyurtmani tasdiqlash]
    Y2 --> F1
    F1 --> F2[Buyurtma qabul qilindi]



  
