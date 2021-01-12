NAMA: ARDHIKA YUDHA PRASETYO
NIM: 19.11.2751

# StudiCase

Program Aplikasi Promos ini adalah pengembangan dari aplikasi sebelumnya dengan menambahkan fitur baru

# Kegunaan
- User dapat melihat daftar makanan yang ditawarkan
- User dapat memasukkan atau menghapus makanan pilihan ke dalam keranjang
- User dapat melihat subtotal makanan yang terdapat pada keranjang
- User dapat melihat daftar voucher yang ditawarkan
- User dapat menggunakan salah satu voucher
- User dapat melihat harga total termasuk potongannya

# Alur Program
 User pertama kali akan ditampilkan halaman MainWindow yang berisikan keranjang, serta subtotal dan total harga.
 User bisa memilih item dengan mengklik nya dan item akan berada di keranjang belanja, disediakan juga voucher yang bisa mengurangi total harga dari keranjang belanja.
 Pemilihan voucher sebagai akhir dari alur aplikasi serta penggunaannya untuk pemotongan harga pada total.


         private void generateContentPenawaran()
		{
			Item coffeLate = new Item("Coffe Late", 30000);
			Item blackTea = new Item("BlackTea", 20000);
			Item pizza = new Item("Pizza", 75000);
			Item milkShake = new Item("Milk Shake", 15000);
			Item friedRice = new Item("Fried Rice Special", 45000);
			Item watermelonJuice = new Item("Watermelon Juice", 25000);
			Item lemonSquash = new Item("Lemon Squash", 30000);

			Penawarancontroller.addItem(coffeLate);
			Penawarancontroller.addItem(blackTea);
			Penawarancontroller.addItem(pizza);
			Penawarancontroller.addItem(milkShake);
			Penawarancontroller.addItem(friedRice);
			Penawarancontroller.addItem(watermelonJuice);
			Penawarancontroller.addItem(lemonSquash);

			listPenawaran.Items.Refresh();
		}

