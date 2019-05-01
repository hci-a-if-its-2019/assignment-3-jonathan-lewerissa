# Usability Evaluation and Prototyping (again)
> Usability Evaluation in this assignment is to evaluate your high-fidelity interactive-prototype with two participants:
> the participant from the previous Contextual Inquiry (CI) 
> and an additional novice-participant with different demographics if possible.
> Respectively, revise your prototype as an attempt to fix any problems found in this Usability Evaluation.

## Operating the Prototype
<!-- > Record a video (screen-recording is preferred) while you operating your prototype.
> Present the ideal case on how to interact with the prototype from the beginning to the end.
> Upload the video on any video-sharing website (e.g., YouTube), then attach the video link on this report. -->

[![Prototype Video](http://img.youtube.com/vi/NMy1xyFa9Pc/0.jpg)](https://www.youtube.com/watch?v=NMy1xyFa9Pc)

---

## Part A: Usability Evaluation
<!-- > In this part, you should prepare your high-fidelity interactive-prototype from the assignment 2.
> Invite the participant from your previous CI to test the prototype.
> You also need to invite one more novice participant.
> As with the CI, you might need to videotape your sessions.
> You can benefit from the videotape while writing your `Recording Transcript` later. -->

### 1. Brief Description of Participants
> Describe your participants in bullets or sentences.
> The description should contain their demographic (age, gender, occupation),
> their skill level in using the system, and your reasons choosing them.
> The description should NOT contain any personally identifiable information.

#### a. Description of Participant 1
- Female
- Less than 20 years old
- Quite good with mobile device and its functionality
- Have been using marketplace app before

#### b. Description of Participant 2
- Female
- More than 50 years old
- A novice with mobile device and its functionality
- Rarely a user of marketplace app

### 2. Evaluation Script
<!-- 
> Write the questions you ask and the instructions you use to direct the participants on what to do.
> If it is the same as previous assignments, please mention this, yet go ahead and INCLUDE it again,
> so we have everything in one place.
> Note that the evaluation script must include exactly what you plan to say to the participants. 
-->

1. Finding the menu and making a transaction for topping up the mobile phone credit.
2. Using promo voucher for transaction.


### 3. Transcript
<!--
> Provide a summary of what the participant did and said, and what you did and said.
> If at some points you have to help the participants, because they cannot figure out what to do,
> that scene must be included in the transcript.
> It is not necessary to write down every word the participant said,
> just what is interesting and useful.
> Ensure to write down all the actions on the device, whether correct or wrong.
> Remember to supplement the transcript with time-codes or line-numbers. 
-->

#### a. Transcript with Participant 1
```
00:30 - A: Jadi ini aplikasi yang akan kamu coba, sekarang kamu diminta untuk membeli pulsa.
00:35 - A: Untuk sementara tombol input untuk nomor HP nya belum bisa digunakan (tidak ada fiturnya di alat desainnya)
00:45 - A: Untuk pembeliannya coba dipilih jumlah harganya.
00:50 - B: Untuk harganya terserah?
00:50 - A: Iya, untuk harganya terserah, sementara coba 20 ribu
01:15 - A: Kemudian, coba pilih fitur pembayaran yang ingin digunakan
01:20 - B: Oke, metode pembayaran sudah dipilih. Langsung ada promonya ya?
01:25 - A: Iya betul, kalau misal promo yang digunakan ingin diganti bagaimana?
01:40 - B: Oke, ini tulisan untuk apa ya? (deskripsi lorem ipsum untuk penjelasan promo)
01:45 - A: Itu fungsi untuk penjelasan promonya
01:55 - B: Oke, coba bayar. Eh, tapi tidak bisa
02:00 - B: (Mencoba update metode pembayaran)
02:05 - B: (Menekan tombol bayar)
02:10 - A: Oke, setelah ini seharusnya akan menunggu status pembayaran berhasil atau tidak
```
#### b. Transcript with Participant 2
```
00:20 - A: Oke, jadi ini sementara aplikasi yang akan dicoba. Jadi, yang perlu dikerjakan adalah membeli pulsa. Untuk fitur pengisian nomor anggap saja sudah terisi, karena fitur pengisian nomor sementara belum ada.
00:40 - B: Iya betul, ini ditekan belum keluar apa-apa.
01:00 - B: Oke, setelah itu coba pilih nilainya, tapi di bagian mana ya?
01:20 - B: Oke ketemu untuk pilih jumlah nilainya.
01:30 - A: Untuk sementara pilih nilai 20 ribu saja.
01:40 - A: Kemudian coba juga jika pembelian ingin menggunakan promo.
01:55 - B: (memilih promo, membaca penjelasannya, tetapi kemudian menekan tombol kembali, dengan asumsi promo sudah terpilih)
02:20 - B: Oke, kemudian pilih ini, payment method. (kemudian memilih bank yang akan digunakan)
02:50 - B: Oke, kemudian bayar.
03:00 - A: Oke, setelah ini seharusnya akan menunggu status pembayaran berhasil atau tidak
```
### 4. Feedback and Incidence Analysis
<!--
> Record your observations per prototype screen followed by reference, feedback, incidence, reason, and resolution.
-->

#### OBSERVATION 1
![Prototype Screen 1](/img/1.png)

 - **Reference**: #1 at 01:40 - 01:45
 - **Feedback**: The #1 participant is confused.
 - **Incidence**: The participant is confused about the function of the page and whether it affects the promo selection.
 - **Reason**: The content of the page is not clear enough, also the feature selection should be exclusively done on the previous screen.
 - **Resolution**: Set this page only as an info screen only.
 
#### OBSERVATION 2
![Prototype Screen 2](/img/2.png)

 - **Reference**: #2 at 01:55
 - **Feedback**: The #2 participant is confused
 - **Incidence**: The participant expected that the promo is selected whenever the button is pressed, but when the screen is moved to the info screen after pressing the promo button and the participant pressed the back button, the promo is not selected. 
 - **Reason**: The application flow doesn't factor in the possibility of using the back button
 - **Resolution**: Factor in the back button.

## Part B: Prototyping (again)
> Next, you will need to modify your prototype 
> based on the resolutions you have suggested in `Feedback and Incidence Analysis`'s observations.

### Sketch
<!-- 
> Draw a sketch of your prototype that is refined based according to the aforementioned observations on a paper.
> Afterwards, scan the sketch or make the photograph of it and attach it on this report's section.
> Please make sure the any texts on the sketch are readable. 
-->

![Sketch of Refined Prototype](/img/lo-fi.jpg)

### Design Rationale
<!--
> Please write a paragraph expressing what you have learned from the usability evaluation, 
> and how it is reflected in your design.
-->

Based on the usabilty evaluation, I have learned that when a user selects a feature, that feature should be immediately selected to avoid user confusion. If not, then provide user feedback to inform the user. In the new design, I have simplified the process of selecting a promo program and moved the information page to a modal based page to improve user experience and flow.

### High-Fidelity Interactive-Prototype
> Create a high-fidelity interactive-prototype based on the `Sketch` you have drawn.
> You can use any prototyping tools: InVision, Adobe XD, or even Microsoft PowerPoint.
