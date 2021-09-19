//inisialisasi variabel
<br>
integer n;
<br>
string hasil;

//eksekusi input
<br>
input n;

//eksekusi proses dan output
<br>
for(int i; i < n; i++){
    <br>
    if(i % 3 == 0){
        <br>
        print hasil = "Fizz";
        <br>
    }else if(i % 5 == 0){
        <br>
        print hasil = "Buzz";
        <br>
    }else if(i % 3 == 0 && i % 5 == 0){
        <br>
        print hasil = "FizzBuzz";
        <br>
    }else{
        <br>
        print hasil = i;
        <br>
    }
    <br>
}