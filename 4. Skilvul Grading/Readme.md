//inisialisasi variabel
<br>
integer nilai_awal, nilai_akhir, sisa;

//eksekusi input
<br>
input nilai_awal;

//eksekusi sisa bagi
<br>
sisa = nilai_awal % 5 < 3;

//eksekusi proses
<br>
if(nilai_awal < 68){
    <br>
    nilai_akhir = nilai_awal;
    <br>
}else if(nilai_awal >= 68){
    <br>
    if(sisa < 3){
        <br>
        nilai_akhir = nilai_awal; 
        <br>
    }else if(sisa >= 3){
        <br>
        if(sisa == 3){
            <br>
            nilai_akhir = nilai_awal + 2; 
            <br>
        }else if(sisa == 4){
            <br>
            nilai_akhir = nilai_awal + 1; 
            <br>
        }else if(sisa == 5){
            <br>
            nilai_akhir = nilai_awal;
            <br> 
        }
        <br>
    }
    <br>
}

//eksekusi output
<br>
print "Hasil : " + nilai_akhir;

