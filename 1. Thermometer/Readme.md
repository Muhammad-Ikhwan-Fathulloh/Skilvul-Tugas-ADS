//Inisilasisai variabel
float suhu;
string tipe = "";
float output_suhu;

//eksekusi input
print "Masukkan suhu anda";
input suhu = "";

print "Masukkan tipe satuan suhu";
input tipe = "";

//eksekusi proses
if (tipe == "fahrenheit "){
    output_suhu = (suhu - 32) * (5/9);
}else if(tipe == "kelvin "){
    output_suhu = (suhu - 273.15);
}else{
    output_suhu = suhu;
}

//tampilkan hasil
print "Suhu Anda : " + output_suhu + " Celcius";

