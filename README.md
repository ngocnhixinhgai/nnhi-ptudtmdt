CREATE TABLE san_pham (
  id INT PRIMARY KEY AUTO_INCREMENT,
  ten_san_pham VARCHAR(100) NOT NULL,
  phan_loai VARCHAR(100) NOT NULL,
  kich_thuoc VARCHAR(30) NOT NULL,
  so_luong_trong_kho VARCHAR(20) NOT NULL,
  mo_ta_san_pham TEXT,
  anh_minh_hoa LONGBLOB
);
