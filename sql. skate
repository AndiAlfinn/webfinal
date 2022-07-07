-- phpMyAdmin SQL Dump
-- version 4.8.5
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Waktu pembuatan: 04 Jul 2022 pada 09.02
-- Versi server: 10.1.38-MariaDB
-- Versi PHP: 7.3.2

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `skate`
--

-- --------------------------------------------------------

--
-- Struktur dari tabel `admin`
--

CREATE TABLE `admin` (
  `id` int(11) NOT NULL,
  `gambar` varchar(100) NOT NULL,
  `nama` varchar(100) NOT NULL,
  `harga` int(11) NOT NULL,
  `kategori` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data untuk tabel `admin`
--

INSERT INTO `admin` (`id`, `gambar`, `nama`, `harga`, `kategori`) VALUES
(1, 'abec11.jpg', 'Bearing Abec 11', 150000, 'Bagian Skateboard'),
(2, 'shakejunt.jpg', 'Griptape Shakejunt', 120000, 'bagian skateboard');

-- --------------------------------------------------------

--
-- Struktur dari tabel `produk`
--

CREATE TABLE `produk` (
  `id` int(11) NOT NULL,
  `foto` varchar(100) NOT NULL,
  `nama` varchar(100) NOT NULL,
  `harga` int(11) NOT NULL,
  `kategori` varchar(100) NOT NULL,
  `Deskripsi` text NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data untuk tabel `produk`
--

INSERT INTO `produk` (`id`, `foto`, `nama`, `harga`, `kategori`, `Deskripsi`) VALUES
(1, '2201022602.jpg', 'Bearing Abec 11', 150000, 'Bagian Skateboard', 'Bearing Abec 11 8 pcs Licin Dan Kencang Buat Skateboard  Buatan indonesia'),
(2, 'shakejunt.jpg', 'Griptape Shake Junt', 120000, 'Bagian Skateboard', 'Griptape Logo Shake junt Hitam Hijau ,kasar dan tahan lama Buatan Indonesia'),
(3, 'bakerungu.jpg', 'Deck Baker Pro Model Rowan', 899000, 'Bagian Skateboard', 'Papan Baker Pro model Rowan Warna Ungu Size 8.0 - 8.25 Free Griptape'),
(4, 'nutsblank.jpg', 'Nuts Blank', 60000, 'Bagian Skateboard', 'Nuts Blank Warna Gold Menggunakan Kunci L'),
(5, 'spitfireclassic.jpg', 'Wheals Spite Fire ', 499000, 'Bagian Skateboard', 'Wheals Spite Fire Classic 53mm , Licin Cocok Di Skatepark dan Street'),
(6, 'creatureset.jpg', 'Deck Creature Set', 175000, 'Skateboard', 'Papan Creature Satu Set Trcuk Creature , Bearing Creature ,Wheals Creature'),
(7, 'grizzlylogo.jpg', 'Griptape Grizzly Logo', 150000, 'Bagian Skateboard', 'Griptape Logo Shake junt Hitam Putih ,kasar dan tahan lama Buatan Indonesia'),
(8, 'shakejuntkuning.png', 'Griptape Shake Junt Yellow', 150000, 'Bagian Skateboard', 'Griptape Logo Shake junt Kuning Hijau ,kasar dan tahan lama Buatan Indonesia');

-- --------------------------------------------------------

--
-- Struktur dari tabel `user`
--

CREATE TABLE `user` (
  `id` int(11) NOT NULL,
  `nama` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `password` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data untuk tabel `user`
--

INSERT INTO `user` (`id`, `nama`, `email`, `password`) VALUES
(6, 'Ma\'ruf', 'muhmaruf0704@gmail.com', '12345');

--
-- Indexes for dumped tables
--

--
-- Indeks untuk tabel `admin`
--
ALTER TABLE `admin`
  ADD PRIMARY KEY (`id`);

--
-- Indeks untuk tabel `produk`
--
ALTER TABLE `produk`
  ADD PRIMARY KEY (`id`);

--
-- Indeks untuk tabel `user`
--
ALTER TABLE `user`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT untuk tabel yang dibuang
--

--
-- AUTO_INCREMENT untuk tabel `admin`
--
ALTER TABLE `admin`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=3;

--
-- AUTO_INCREMENT untuk tabel `produk`
--
ALTER TABLE `produk`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=9;

--
-- AUTO_INCREMENT untuk tabel `user`
--
ALTER TABLE `user`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=7;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
