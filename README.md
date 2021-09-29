Laporan Tugas Git
1. Inisialisi repository melalui Git (CLI)
	a. Buat folder baru untuk local repository
	b. Klik kanan dan pilih "Git Bash Here"
	c. Initialize repository dengan command "git init"
2. Buat Clone Repository di GitHub
	a. Login ke GitHub
	b. Buat Repository Baru dengan nama "Tugas_Repo_Git"
3. Buat file README.md lalu edit isinya sesuai dengan tugas laporan
	a. Buat file README.md dengan command "touch README.md"
	b. Edit file README.md dengan command "nano README.md"
	c. Simpan README.md yang sudah diubah dengan ctrl + o, lalu tekan enter
	d. Keluar dari nano dengan menekan ctrl + x
4. First Commit file README.md ke repositori yang sudah dibuat tadi
	a. Lakukan remote repository GitHub dengan command "git remote add origin https://github.com/AuliaHibatillah/Tugas_Repo_Git"
	b. Menambahkan README.md ke staging area dengan command "git add README.md"
	c. Cek status repositori dengan command "git status"
	d. Commit dengan command "git commit -m 'Commit Pertama'"
	e. Lalu Push commit tadi ke repositori github dengan command "git push origin main"
	f. Akses dan buat token github melalui developer setting > personal access token dan copy dan paste token tersebut ke window yang akan muncul setelah kita push commit tadi.
	g. Selesai
 
