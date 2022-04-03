
<?php

echo "3de0d2bc-4fb2-4651-15de-c98ad453eee4";
echo "<br>";

function rla ($len_of_gen_str){
    $chars = "abcdefghijklmnopqrstuvwxyz";
    $var_size = strlen($chars);
    for( $x = 0; $x < $len_of_gen_str; $x++ ) {  
        $random_str= $chars[ rand( 0, $var_size - 1 ) ];  
        echo $random_str;  
    }
}


function rni ($len_of_gen_str){
    $chars = "1234567890";
    $var_size = strlen($chars);
    for( $x = 0; $x < $len_of_gen_str; $x++ ) {  
        $random_str= $chars[ rand( 0, $var_size - 1 ) ];  
        echo $random_str;  
    }
}

function bypass(){
    #esta função é responsável por bypassar o id da transação de pagamento
    $n1 = rni(1).rla(2).rni(1).rla(1).rni(1).rla(2);
    echo "-";
    $n2 = rni(1).rla(2).rni(1);
    echo "-";
    $n3 = rni(4);
    echo "-";
    $n4 = rni(2).rla(2);
    echo "-";
    $n5 = rla(1).rni(2).rla(2).rni(3).rla(3).rni(1);
}

bypass();
