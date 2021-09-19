//Inisilasisai variabel
<br>
float suhu;
<br>
string tipe = "";
<br>
float output_suhu;

//eksekusi input
<br>
print "Masukkan suhu anda";
<br>
input suhu = "";
<br>
print "Masukkan tipe satuan suhu";
<br>
input tipe = "";

//eksekusi proses
<br>
if (tipe == "fahrenheit "){
    <br>
    output_suhu = (suhu - 32) * (5/9);
    <br>
}else if(tipe == "kelvin "){
    <br>
    output_suhu = (suhu - 273.15);
    <br>
}else{
    <br>
    output_suhu = suhu;
    <br>
}

//tampilkan hasil
<br>
print "Suhu Anda : " + output_suhu + " Celcius";

