TugasProcedurMenghitungLuas
===========================

package id.blits.Tugas;


public class NewMainMenu {

 
    public static void main(String[] args) {
        // TODO code application logic here
        PersegiPanjang Pp =  new  PersegiPanjang();
        Pp.nama="Persegi Panjang";
        Pp.Panjang=20;
        Pp.Lebar=12;
        
        Pp.tampilPersegiPanjang();
        
        Segitiga SegiT = new Segitiga();
        SegiT.nama="Menghitung Luas Segi Tiga";
        SegiT.Alas=25;
        SegiT.Tinggi=30;
        
        SegiT.tampilSegiTiga();
        
        Lingkaran Ida = new  Lingkaran();
        Ida.nama="Menghitung Luas Lingkaran";
        Ida.Jari2=20;
        
        Ida.tampilLingkaran();

        

        
    }
    
}
