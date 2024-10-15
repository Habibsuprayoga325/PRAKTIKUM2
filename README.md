# praktikum2 person
```
NAMA    : HABIB SUPRAYOGA
NIM     : 312310608
KELAS   : TI.23.A6
MATKUL  : Pemrograman Orientasi Objek
```

## Latihan
-   Buat kode java mendeklarasikan class Person dengan atribut Nama, JenisKelamin, Umur. Lengkap dengan access modifier nya.
-   Lalu buat objek class person bernama Anton & Riko.

### Class Person
- Atribut
```
public class Person2 {

    private String nama;
    private String jenisKelamin;
    private int umur;
```
![image](SS3/ss1.png)

- Konstruktor
```
public Person2(String nama, String jenisKelamin, int umur) {
        this.nama = nama;
        this.jenisKelamin = jenisKelamin;
        this.umur = umur;
    }
```
![image](SS3/ss2.png)

- Setter Nama
```
public void setNama(String nama) {
        this.nama = nama;
    }
```
![image](SS3/ss3.png)

- Getter Nama
```
public String getNama() {
        return nama;
    }
```
![image](SS3/ss4.png)

- Setter JenisKelamin
```
public void setJenisKelamin(String jenisKelamin) {
        this.jenisKelamin = jenisKelamin;
    }
```
![image](SS3/ss5.png)

- Getter JenisKelamin
```
public String getJenisKelamin() {
        return jenisKelamin;
    }
```
![image](SS3/ss6.png)

- Setter Umur
```
public void setUmur(int umur) {
        this.umur = umur;
    }
```
![image](SS3/ss7.png)

- Getter Umur
```
public int getUmur() {
        return umur;
    }
```
![image](SS3/ss8.png)

- Menampilkan informasi person
```
public void displayInfo() {
        System.out.println("Nama: " + nama);
        System.out.println("Jenis Kelamin: " + jenisKelamin);
        System.out.println("Umur: " + umur);
    }
```
![image](SS3/ss9.png)

- Main method & membuat 2 objek untuk Anton&Riko
```
public static void main(String[] args) {
        Person2 antot = new Person2("Antot", "Laki-laki", 18);
        Person2 riko = new Person2("Riko", "Laki-laki", 18);
```
![image](SS3/ss10.png)

- menampilkan informasi awal
```
System.out.println("Informasi Awal:");
        antot.displayInfo();
        System.out.println();
        riko.displayInfo();
    }
}
```
![image](SS3/ss11.png)

- Output
```
Informasi Awal:
Nama: Antot
Jenis Kelamin: Laki-laki
Umur: 18

Nama: Riko
Jenis Kelamin: Laki-laki
Umur: 18

```
![image](SS3/ss12.png)

