<h1>Базированная база</h1>

<h2>Задание:</h2>
Описания нет

<h2>Решение:</h2>
<pre lang="python">
<code>
SEFZQ0FNSlJHRVFEQ01CWUVBWVRFTUpBR1kzU0FPQlVFQTNUQUlCUkdJWlNBTkJaRUEyVEtJQlpHVVFESU9KQUdVWlNBT0pWRUE0VFFJQlZHSVFES01aQUdVWVNBTUpTR1U9PT09PT0=
</code>
</pre>

Существует множество систем счисления, от очевидных, до не очень очевидных. В этом задании перед нами один из таких примеров неочевидных систем счисления. Данная строка представляет из себя шифротекст base32, алфавит которой состоит только из заглавных букв английского алфавита и цифр от нуля до 9. Если знать достаточно критериев определения шифра с помошью которого зашифровано конкретное сообщение, то можно опрделять каким именно образом было зашифрованно то или иное сообщение. Чтож, раз это base32, то необходимо просто прогнать шифротекст через дешифратор в интернете и получить другую строчку.
