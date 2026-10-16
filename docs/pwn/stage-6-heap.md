# Stage 6 – Heap

## Bạn sẽ học được gì?

- [ ] Cấu trúc chunk của glibc malloc
- [ ] Bins: tcache, fastbin, unsorted, small, large
- [ ] UAF, double free, heap overflow
- [ ] Tcache poisoning
- [ ] Leak libc qua unsorted bin
- [ ] Safe-linking

## 1. Lý thuyết

_TODO: giải thích ngắn gọn, có hình/sơ đồ._

## 2. Demo từng bước

_TODO: một ví dụ chạy được, có lệnh GDB/pwntools và output._

## 3. Lab tự làm

_TODO: bài nhỏ tự dựng, kèm source và cách build._

## 4. Bài CTF áp dụng

_TODO: 2-3 bài thật. Chỉ dẫn link, không đăng writeup của giải đang diễn ra._

!!! tip "Mốc kiểm tra"
    Giải được một bài heap menu-style (add/edit/delete/show) trên glibc hiện đại.

## Tài nguyên

- how2heap
- pwn.college (module Heap)
- pwnable.tw

---

- Trước: [Stage 5 – Stack nâng cao](stage-5-stack-nang-cao.md)
- Tiếp: [Stage 7 – Heap nâng cao và hardening hiện đại](stage-7-heap-nang-cao.md)
