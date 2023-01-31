# Pada diagram entity tersebut ada 4 table database

- users
- expense
- category
- monthly_incomes

# Table user memilikli relasi dengan expense dan monthly_incomes :

- OneToOne Relation dengan monthly_incomes dengan jenis cardinality "Zero or One" karna satu user dalam satu bulan bisa saja lagi bokek dan tidak punya pemasukan atau punya pemasukan ( Semua sumber pemasukan ditotal jadi satu), dan "One and only one" sebagai mandatory atau wajib pemasukan terkait ke seorang user

- OneToMany relation dengan expense yang membuat satu user bisa memiliki banyak jenis expense dengan jenis cardinality "Zero or Many" karbna dalam satu hari bisa saja user ngirit untuk ditabung, sedangkan cardinality expense untuk user adalah "One and only one" karna expense harus terkait ke salah satu user dan berbeda deskripsi pengeluaran nya antar user lain

# Table expense berelasi dengan table category :

- ManyToOne Relation antara expense dengan category, line cardinality dari expense ke category adalah "One and only one" sedangkan category ke expense adalah "One or Many" karna satu category bisa memiliki banyak jenis expense
