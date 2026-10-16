# Stage 4 – Format string

## Bạn sẽ học được gì?

- [ ] Tìm offset của format string
- [ ] Leak stack/canary/PIE/libc
- [ ] Arbitrary read bằng `%s`
- [ ] Arbitrary write bằng `%n`
- [ ] GOT overwrite

## 1. Lý thuyết

_TODO: giải thích ngắn gọn, có hình/sơ đồ._

## 2. Demo từng bước

_TODO: một ví dụ chạy được, có lệnh GDB/pwntools và output._

## 3. Lab tự làm

_TODO: bài nhỏ tự dựng, kèm source và cách build._

## 4. Bài CTF áp dụng

_TODO: 2-3 bài thật. Chỉ dẫn link, không đăng writeup của giải đang diễn ra._

!!! tip "Mốc kiểm tra"
    Chain format string để leak rồi ghi đè được GOT.

## Tài nguyên

- exploit.education (Phoenix)
- Nightmare (guyinatuxedo)

---

- Trước: [Stage 3 – Shellcode và ROP](stage-3-shellcode-rop.md)
- Tiếp: [Stage 5 – Stack nâng cao](stage-5-stack-nang-cao.md)
