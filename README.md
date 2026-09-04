# Fancy Tower — Tài liệu dự án

Repository **nguồn sự thật về tài liệu** cho dự án **MỚI**: website giới thiệu và
bán căn hộ chung cư.

> 🔀 Đây **KHÔNG** phải repository tài liệu của website doanh nghiệp Thiên Đức đang
> vận hành. Tài liệu hệ thống hiện tại nằm ở repository riêng:
> [`../thien-duc-website-docs/`](../thien-duc-website-docs/)

⚠️ **Lưu ý phân biệt:** website Thiên Đức hiện tại có một dự án tên *Fancy Tower*
(chung cư thuộc Khu đô thị Hưng Phú). Tài liệu về nội dung dự án đó trên website công
ty thuộc repo Thiên Đức. Repo này chỉ chứa tài liệu của **sản phẩm bán căn hộ mới**.

## Trạng thái hiện tại

| Giai đoạn | Trạng thái |
|---|---|
| Giai đoạn 0 — Rà soát hệ thống hiện tại | ✅ **HOÀN TẤT** |
| Giai đoạn 0.5 — Lập phiếu quyết định | ✅ **HOÀN TẤT TÀI LIỆU** |
| Quyết định của Ban lãnh đạo (A1–A10) | 🔴 **ĐANG MỞ — 0/10 đã phê duyệt** |
| Giai đoạn 0.6 — Thẩm định quyết định | ✅ **HOÀN TẤT — Cổng 1 KHÔNG ĐẠT** |
| Giai đoạn 1 — Thiết kế kỹ thuật | ⬜ **CHƯA BẮT ĐẦU** |
| Giai đoạn 2 — Viết mã nguồn | ⬜ **CHƯA BẮT ĐẦU** |

**Việc viết mã nguồn bắt đầu ở GIAI ĐOẠN 2.** Giai đoạn 1 chỉ là thiết kế kỹ thuật
trên giấy, không viết mã nguồn.

## Tài liệu chính

| Vai trò | Tài liệu |
|---|---|
| **NGUỒN SỰ THẬT** — tổng quan nghiệp vụ & kỹ thuật | [02-technical-proposal/Bao-cao-phuong-an-ky-thuat-Website-Gioi-thieu-va-Ban-Chung-Cu.docx](02-technical-proposal/Bao-cao-phuong-an-ky-thuat-Website-Gioi-thieu-va-Ban-Chung-Cu.docx) |
| **TÀI LIỆU QUYẾT ĐỊNH ĐANG HOẠT ĐỘNG** | [03-decisions/Decision-Pack-Website-Ban-Chung-Cu.docx](03-decisions/Decision-Pack-Website-Ban-Chung-Cu.docx) |

**Người mới bắt đầu ở đây:** đọc Báo cáo phương án kỹ thuật. Tài liệu đó đã hợp nhất
phần tổng quan của toàn bộ các báo cáo trước, đủ để ra quyết định ở cấp lãnh đạo.

## Bằng chứng đã lưu trữ

| Tài liệu | Vì sao lưu trữ |
|---|---|
| [archive/phase-0/](archive/phase-0/) — Báo cáo rà soát Giai đoạn 0 | Phần tổng quan đã được thay thế bởi Báo cáo phương án kỹ thuật. Giữ lại vì chứa bằng chứng kỹ thuật chi tiết. Chỉ mở khi cần kiểm chứng một kết luận. |

## Trạng thái ba cổng quyết định

| Cổng | Kết quả | Lý do |
|---|---|---|
| **Cổng 1** — Sẵn sàng thiết kế kỹ thuật | 🔴 **KHÔNG ĐẠT** | 0/7 điều kiện đạt: chưa chốt A1, A2, A3, A5, A7, A8 và chưa có dữ liệu rổ hàng mẫu |
| **Cổng 2** — Sẵn sàng triển khai xây dựng | 🔴 **KHÔNG ĐẠT** | Chưa tới lượt xét — Giai đoạn 1 chưa diễn ra |
| **Cổng 3** — Sẵn sàng chạy thật | 🔴 **KHÔNG ĐẠT** | 0/7 điều kiện đạt: chưa có A9 (pháp lý), A10 (hạ tầng), A4 (chủ dữ liệu), sao lưu, giám sát |

## Việc cần làm tiếp theo

Ban lãnh đạo cần chốt **sáu quyết định** để mở khoá Giai đoạn 1:

| Mã | Quyết định |
|---|---|
| **A1** | Website bán cho MỘT dự án hay NHIỀU dự án? |
| **A2** | Chính sách công khai giá (kèm xác nhận của Pháp chế) |
| **A3** | Có công khai tình trạng bán của từng căn không? |
| **A5** | Dữ liệu rổ hàng và giá gốc nằm ở đâu? |
| **A7** | Nhân viên kinh doanh có cần tài khoản CMS không? |
| **A8** | Dùng chung hệ thống hiện tại hay tách riêng? |

Kèm theo: **một tệp rổ hàng thật làm mẫu** (một toà nhà là đủ) do bộ phận Kinh doanh
cung cấp — dùng để thiết kế mô hình dữ liệu, không phải để nhập vào hệ thống thật.

### Sổ hành động

| Mã | Việc cần làm | Liên quan | Chịu trách nhiệm | Chặn cổng |
|---|---|---|---|---|
| ACT-01 | Tổ chức cuộc họp phê duyệt phiếu quyết định | A1–A10 | Ban lãnh đạo | Cổng 1 |
| ACT-02 | Chốt phạm vi một hay nhiều dự án | A1 | Ban lãnh đạo | Cổng 1 |
| ACT-03 | Chốt chính sách giá + ý kiến pháp chế bằng văn bản | A2 | Ban lãnh đạo + Pháp chế | Cổng 1 |
| ACT-04 | Chốt trạng thái công khai / nội bộ; cung cấp cách gọi thực tế | A3 | Ban lãnh đạo + Kinh doanh | Cổng 1 |
| ACT-05 | Chốt nguồn dữ liệu gốc chính thức (chỉ chọn MỘT) | A5 | Kinh doanh | Cổng 1 |
| ACT-06 | Chốt có bổ sung vai trò KINH DOANH hay không | A7 | Ban lãnh đạo | Cổng 1 |
| ACT-07 | Chốt phương án kiến trúc A / B / C | A8 | Ban lãnh đạo + Kỹ thuật | Cổng 1 |
| ACT-08 | Cung cấp tệp rổ hàng thật làm mẫu | A5 | Kinh doanh | Cổng 1 |
| ACT-09 | Chốt ma trận quyền sửa và duyệt giá / tình trạng | A6 | Kinh doanh + Ban lãnh đạo | Cổng 2 |
| ACT-10 | Chọn phạm vi 31 tính năng MVP và đóng băng | MVP | Ban lãnh đạo | Cổng 2 |
| ACT-11 | Xác nhận danh sách hạng mục ngoài phạm vi | Ngoài MVP | Ban lãnh đạo | Cổng 2 |
| ACT-12 | Chỉ định bằng văn bản chủ sở hữu dữ liệu rổ hàng | A4 | Kinh doanh | Cổng 3 |
| ACT-13 | Pháp chế phê duyệt từng dự án được đăng công khai | A9 | Pháp chế | Cổng 3 |
| ACT-14 | Phê duyệt ngân sách hạ tầng và sao lưu | A10 | Ban lãnh đạo | Cổng 3 |
| ACT-15 | Chạy lại thẩm định sau khi phiếu được điền; lập Decision Register mới | Toàn bộ | Kỹ thuật | Cổng 1 |

## Cấu trúc thư mục

```
thien-duc-website-fancy-tower-docs/
├── README.md                  ← file này (điểm vào của dự án)
├── 00-overview/               tổng quan, phạm vi, thuật ngữ          (Giai đoạn 1)
├── 01-business/               yêu cầu nghiệp vụ, hồ sơ pháp lý       (Giai đoạn 1)
├── 02-technical-proposal/     ★ NGUỒN SỰ THẬT — phương án kỹ thuật
├── 03-decisions/              ★ phiếu quyết định A1–A10 + ADR
├── 04-architecture/           kiến trúc chi tiết, ERD, đặc tả API    (Giai đoạn 1)
├── 05-implementation/         kế hoạch và trạng thái triển khai      (Giai đoạn 2+)
├── 06-testing/                chiến lược và kết quả kiểm thử         (Giai đoạn 5)
├── 07-deployment/             triển khai, hạ tầng, vận hành          (Giai đoạn 6)
├── 08-audits-and-reports/     báo cáo có ngày                        (Giai đoạn 1+)
└── archive/
    └── phase-0/               báo cáo rà soát Giai đoạn 0 (bằng chứng)
```

Các thư mục chưa có nội dung là **khung có chủ đích** cho các giai đoạn sau, không
phải thiếu sót.

## Nguồn sự thật

| Thứ tự | Loại thông tin | Nguồn chuẩn |
|---|---|---|
| 1 | Tổng quan nghiệp vụ + kỹ thuật | Báo cáo phương án kỹ thuật (`02-technical-proposal/`) |
| 2 | Quyết định đã được phê duyệt | Decision Register — **chưa tồn tại**, lập sau khi phiếu được điền |
| 3 | Thiết kế kỹ thuật chi tiết (ADR, ERD, API) | `04-architecture/` — **chưa tồn tại** (Giai đoạn 1) |
| 4 | Kế hoạch triển khai | `05-implementation/` — **chưa tồn tại** (Giai đoạn 2) |
| 5 | Kiểm thử và triển khai vận hành | `06-testing/`, `07-deployment/` — **chưa tồn tại** |
| — | Quyết định đang chờ Ban lãnh đạo | Phiếu quyết định (`03-decisions/`) — **đang hoạt động** |
| — | Bằng chứng rà soát ban đầu | `archive/phase-0/` — lưu trữ, không phải nguồn sự thật |

## Phụ thuộc bên ngoài

Dự án này mở rộng từ nền tảng Thiên Đức đang vận hành. Tài liệu hệ thống đó nằm ở
repository riêng và **thuộc quyền sở hữu của repo đó** — không sao chép sang đây:

| Cần tra cứu | Đọc ở |
|---|---|
| Kiến trúc hệ thống hiện tại | [`../thien-duc-website-docs/02-architecture/`](../thien-duc-website-docs/02-architecture/) |
| Trạng thái module hiện tại | [`../thien-duc-website-docs/04-implementation/module-status.md`](../thien-duc-website-docs/04-implementation/module-status.md) |
| Bảo mật hệ thống hiện tại | [`../thien-duc-website-docs/05-security/`](../thien-duc-website-docs/05-security/) |
| Triển khai và hạ tầng hiện tại | [`../thien-duc-website-docs/07-deployment/`](../thien-duc-website-docs/07-deployment/) |
| Quyết định kiến trúc hiện hành (ADR) | [`../thien-duc-website-docs/10-decisions/`](../thien-duc-website-docs/10-decisions/) |

> Nếu quyết định **A7** được phê duyệt (bổ sung vai trò Kinh doanh), phải lập một ADR
> mới trong repo này **thay thế** `ADR-0002-rbac-three-roles.md` của repo Thiên Đức.

## Quy ước

- Thư mục & file Markdown: **chữ thường, kebab-case, tiếng Anh, không dấu**.
- Báo cáo có ngày: `YYYY-MM-DD-ten-bao-cao.md`.
- ADR: `ADR-FT-XXXX-tieu-de.md`.
- Báo cáo Word trình lãnh đạo giữ tên mô tả tiếng Việt đã thiết lập.
- Nội dung *bên trong* file viết tiếng Việt.
- Secret/token/mật khẩu **không bao giờ** được đưa vào repo này.

Quy ước đầy đủ (chủ sở hữu chuẩn):
[`../thien-duc-website-docs/documentation-conventions.md`](../thien-duc-website-docs/documentation-conventions.md).
