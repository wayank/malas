malas
=====

jQuery funy autocomple
Dependencies : jquery.1.8

example :
<html>
<head>
<script type="text/javascript" src="http://code.jquery.com/jquery-latest.js"></scipt>
</head>
<body>

<input type="text" class="nbarang"/>
<input type="text" class="mbarang"/>
<input type="text" class="sbarang"/>
<input type="text" class="stbarang"/>
<input type="text" class="hbarang"/>

<script type:"text/javascript" >
  var data =[
				["Pulpen", "Snowman", "-", "Buah", "2.600"],
				["Spidol", "Snowman", "-", "Buah", "8.250"],
				["Tinta Stempel", "-", "-", "Botol", "24.700"],
				["Bantal Stempel", "-", "-", "Buah", "2.730"],
				["Hekter", "-", "Besar", "Buah", "16.000"],
				["Hekter", "-", "Kecil", "Buah", "6.500"],
				["Peluru Hekter", "-", "Besar", "Box", "49.400"],
				["Peluru Hekter", "-", "Kecil", "Box", "22.100"],
				["Amplop Panjang", "-", "Polos", "Dos", "14.300"],
				["Map Ordener", "-", "-", "Buah", "11.700"],
				["Tip-ex", "-", "-", "Dos", "7.020"],
				["Lem", "Agung", "Besar", "Buah", "6.110"],
				["Kertas HVS", "-", "Tanpa Kop", "Rim", "47.250"],
				["Map Plastik", "-", "-", "Buah", "1.300"],
				["Map Plastik", "-", "Tusuk", "Buah", "3.250"],
				["Map Biasa", "-", "-", "Lembar", "750"],
				["Map Besi", "-", "-", "Buah", "6.750"],
				["Map Schnelhecter", "-", "-", "Buah", "1.500"],
				["Pisau Cutter", "-", "-", "Buah", "13.000"],
				["Buku Tulis", "-", "Besar Isi 100 Lbr", "Buah", "13.000"],
				["Buku Tulis", "-", "Kecil Isi 100 Lbr", "Buah", "6.500"],
				["Isolasi Jilid", "-", "Besar", "Buah", "14.040"],
				["Pulpen Balliner", "-", "-","Buah", "17.550"]
			];
		
		$(".nbarang, .mbarang, .sbarang, .hbarang").malas(data);
</script>
</body>
</html>
