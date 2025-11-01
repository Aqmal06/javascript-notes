# javascript-notes
-> Basic JavaScript  
1.<script><script>  
2.document.body.innerHTML  
3.alert();  
 -> (untuk create pop up)  
4.typeof 'value'  
 -> (untuk check data type input)  
5.onclick=""  
 -> (terpakai dalam element button)  

-> Javascript follow order of operations  
 Bermula dengan Bracket -> multiply/division ->plus/minus  
-> Calculation  
 -> pakai int, kemudian convert kepada float dengan divide 100  
 -> Math.round(n) untuk bundar  

-> JavaScript ada 3 types of string  
 -> 1.single quote  
 -> 2.double quote  
    -> Escape characters (digunakan bila character/huruf pakai koma atas) (\' atau \")  
    -> digunakan untuk create baris baharu(\n)  
 -> 3.interpolation  
    -> gunakan '$' dan 'curly braces' untuk munculkan input  

-> JavaScript comparasion operator  
 -> (==)  
   -> tanda equals 2 akan convert kedua-dua value menjadi types yang sama  
   -> data type value kanan akan convert menjadi data type kiri  
 -> (===)  
   -> untuk avoid syntax error dalam comparasion, pakai equals 3.  
-> Truthy dan Falsy act seperti True dan False  
   -> falsy value ialah: 0, '', NaN, undefined, null  
   -> truthy value ialah: bukan yang disenaraikan di atas  
-> Ternary operator Javascript boleh assigned variable  
