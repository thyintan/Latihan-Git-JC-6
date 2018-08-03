    Masukkan angka 1: <input id="nomor1" type="number">
            <br/>
    Masukkan angka 2: <input id="nomor2" type="number"> 

    <button onclick="fungsiKu()"> Pangkatkan! </button>
    <p id="pangkat"> Hasil </p>
    
    <script>
        function fungsiKu() {
            let AngkaKamu1 = document.getElementById("nomor1").value;
            let AngkaKamu2 = document.getElementById("nomor2").value;
            let AngkaHasil = parseInt(AngkaKamu1)^parseInt(AngkaKamu2);
        }
    
    document.getElementById("pangkat").innerHTML = AngkaHasil;
    </script>
