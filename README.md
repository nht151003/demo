# Hàm tính trung bình của một dãy số
def tinh_trung_binh(danh_sach):
    if len(danh_sach) == 0:
        return 0  # Tránh chia cho 0
    tong = sum(danh_sach)
    trung_binh = tong / len(danh_sach)
    return trung_binh

# Ví dụ sử dụng
danh_sach_so = [1, 2, 3, 4, 5]
trung_binh = tinh_trung_binh(danh_sach_so)
print("Trung bình của dãy số là:", trung_binh)
