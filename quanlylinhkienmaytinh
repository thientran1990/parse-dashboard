-- phpMyAdmin SQL Dump
-- version 4.5.1
-- http://www.phpmyadmin.net
--
-- Host: 127.0.0.1
-- Generation Time: Aug 18, 2016 at 04:10 PM
-- Server version: 10.1.10-MariaDB
-- PHP Version: 5.6.19

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `quanlylinhkienmaytinh`
--

-- --------------------------------------------------------

--
-- Table structure for table `cthoadon`
--

CREATE TABLE `cthoadon` (
  `MaHoaDon` varchar(50) NOT NULL,
  `tenKH` varchar(50) NOT NULL,
  `Diachi` varchar(50) NOT NULL,
  `DSSanpham` varchar(50) NOT NULL,
  `Tonggia` int(50) NOT NULL,
  `Ngay` varchar(50) NOT NULL,
  `Trangthaidonhang` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `cthoadon`
--

INSERT INTO `cthoadon` (`MaHoaDon`, `tenKH`, `Diachi`, `DSSanpham`, `Tonggia`, `Ngay`, `Trangthaidonhang`) VALUES
('hd1', 'hu?nh v?n tèo', '116 noi nao do', 'AK Racing Dignitas Black/White - Special Edition', 8499000, '29/7/16', '?ang giao'),
('hd2', 'tèo v?n hu?nh', '116 noi nào ?ó', '', 0, '', ''),
('hd3', 'tèo v?n hu?nh', '116 noi nào ?ó', '', 0, '', ''),
('hd4', 'tèo v?n hu?nh', '116 noi nào ?ó', '', 0, '', ''),
('hd5', 'tèo v?n hu?nh', '116 noi nào ?ó', '', 0, '', '');

-- --------------------------------------------------------

--
-- Table structure for table `dssanpham`
--

CREATE TABLE `dssanpham` (
  `hotenKH` varchar(50) NOT NULL,
  `MaSP` varchar(50) NOT NULL,
  `TenSP` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

-- --------------------------------------------------------

--
-- Table structure for table `khachhang`
--

CREATE TABLE `khachhang` (
  `hotenKH` varchar(50) NOT NULL,
  `email` varchar(50) NOT NULL,
  `SDT` int(50) NOT NULL,
  `DiaChi` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `khachhang`
--

INSERT INTO `khachhang` (`hotenKH`, `email`, `SDT`, `DiaChi`) VALUES
('1', '1', 1, '1'),
('huynh van teo', 'teo4@gmail.com', 26549875, '116 noi nao do'),
('teo van huyenh', 'teo1@gmail.com', 26549875, '116 noi nao do'),
('V?n v?n tèo', 'teo5@gmail.com', 26549875, '116 noi nao do'),
('van huyenh teo', 'teo2@gmail.com', 26549875, '116 noi nao do');

-- --------------------------------------------------------

--
-- Table structure for table `loaisp`
--

CREATE TABLE `loaisp` (
  `MaLoai` varchar(50) NOT NULL,
  `TenLoai` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `loaisp`
--

INSERT INTO `loaisp` (`MaLoai`, `TenLoai`) VALUES
('bg', 'banghe'),
('bp', 'banphim'),
('c', 'chuot'),
('mp', 'mousepad'),
('tn', 'tainghe');

-- --------------------------------------------------------

--
-- Table structure for table `sanpham`
--

CREATE TABLE `sanpham` (
  `MaSP` varchar(50) NOT NULL,
  `TenSP` varchar(50) NOT NULL,
  `MaLoai` varchar(50) NOT NULL,
  `Gia` int(50) NOT NULL,
  `Baohanh` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `sanpham`
--

INSERT INTO `sanpham` (`MaSP`, `TenSP`, `MaLoai`, `Gia`, `Baohanh`) VALUES
(' i-Rocks K62E ', 'i-Rocks K62E - White', 'bp', 589000, '12'),
('1', '2', '2', 2, '2'),
('AK-Racing Dignitas Special Edition  ', 'AK Racing Dignitas Black/White - Special Edition', 'bg', 8499000, '24'),
('KR6260WE', 'i-Rocks 6260WE', 'bp', 549000, '0'),
('Leopold Keycaps Set 10TH A   ', 'Leopold Keycaps Leopold Set 10TH A', 'bp', 1350000, '12'),
('STEELSERIES SIBERIA 200 ALCHEMY GOLD', 'STEELSERIES SIBERIA 200 ALCHEMY GOLD', 'tn', 1690000, '12');

--
-- Indexes for dumped tables
--

--
-- Indexes for table `cthoadon`
--
ALTER TABLE `cthoadon`
  ADD PRIMARY KEY (`MaHoaDon`);

--
-- Indexes for table `khachhang`
--
ALTER TABLE `khachhang`
  ADD PRIMARY KEY (`hotenKH`);

--
-- Indexes for table `loaisp`
--
ALTER TABLE `loaisp`
  ADD PRIMARY KEY (`MaLoai`);

--
-- Indexes for table `sanpham`
--
ALTER TABLE `sanpham`
  ADD PRIMARY KEY (`MaSP`);

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
