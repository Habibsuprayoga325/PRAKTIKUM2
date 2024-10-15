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
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss1.png?raw=true)
- Konstruktor
```
public Person2(String nama, String jenisKelamin, int umur) {
        this.nama = nama;
        this.jenisKelamin = jenisKelamin;
        this.umur = umur;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss2.png?raw=true)
- Setter Nama
```
public void setNama(String nama) {
        this.nama = nama;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss3.png?raw=true)

- Getter Nama
```
public String getNama() {
        return nama;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss4.png?raw=true)

- Setter JenisKelamin
```
public void setJenisKelamin(String jenisKelamin) {
        this.jenisKelamin = jenisKelamin;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss5.png?raw=true)

- Getter JenisKelamin
```
public String getJenisKelamin() {
        return jenisKelamin;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss6.png?raw=true)

- Setter Umur
```
public void setUmur(int umur) {
        this.umur = umur;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss7.png?raw=true)

- Getter Umur
```
public int getUmur() {
        return umur;
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss8.png?raw=true)

- Menampilkan informasi person
```
public void displayInfo() {
        System.out.println("Nama: " + nama);
        System.out.println("Jenis Kelamin: " + jenisKelamin);
        System.out.println("Umur: " + umur);
    }
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss9.png?raw=true)

- Main method & membuat 2 objek untuk Anton&Riko
```
public static void main(String[] args) {
        Person2 antot = new Person2("Antot", "Laki-laki", 18);
        Person2 riko = new Person2("Riko", "Laki-laki", 18);
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss10.png?raw=true)

- menampilkan informasi awal
```
System.out.println("Informasi Awal:");
        antot.displayInfo();
        System.out.println();
        riko.displayInfo();
    }
}
```
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss11.png?raw=true)

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
![alt text](https://github.com/Habibsuprayoga325/PRAKTIKUM2/blob/main/ss12.png?raw=true)

