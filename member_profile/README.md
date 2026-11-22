# RomDev Knowledge — Thư Viện Tri Thức & Nghiên Cứu Kỹ Thuật

Tổ chức lưu trữ tập trung các **kho tri thức kỹ thuật, tài liệu nghiên cứu chuyên sâu và bản dịch tiếng Việt** (triển khai đọc trực tuyến riêng tư trên Cloudflare Workers + Zero Trust Access), tách riêng khỏi các tổ chức phát triển mã nguồn & công cụ (`RomDev-Tool`, `RomDev-Hub`) để dễ tra cứu và lưu trữ lâu dài.

- **Cổng danh mục trung tâm (riêng tư):** https://go.romdev-knowledge.workers.dev/
- **Quy tắc mở nhanh kho mới:** `https://go.romdev-knowledge.workers.dev/<slug>` (tự động chuyển hướng sang `https://<slug>.romdev-knowledge.workers.dev/`)

## Danh Mục Kho Tri Thức Hiện Có

| Kho lưu trữ | Chủ đề trọng tâm | Cổng mở nhanh (`/go`) & URL trực tiếp |
| --- | --- | --- |
| [rom-research-autonomous-vehicle-industry](https://github.com/RomDev-Knowledge/rom-research-autonomous-vehicle-industry) | Công nghệ Xe tự hành, Perception, SLAM, World Models, MLOps & Vận hành Khu bay (909 tài liệu · 137 sơ đồ SVG tiếng Việt) | [Mở qua cổng `/go`](https://go.romdev-knowledge.workers.dev/rom-research-autonomous-vehicle-industry) · [URL trực tiếp](https://rom-research-autonomous-vehicle-industry.romdev-knowledge.workers.dev/) |

## Quy Ước Đặt Tên Kho

- `rom-research-<slug>`: Kho tổng hợp nghiên cứu chuyên sâu / bản dịch học thuật kèm giao diện đọc VitePress.
- `rom-kb-<slug>` / `rom-knowledge`: Ghi chú tri thức, sổ tay kỹ thuật (`guides/`, `playbooks/`, `notes/`).
- Mọi kho được triển khai lên Cloudflare Workers dưới subdomain `romdev-knowledge.workers.dev` đều mở được ngay qua quy tắc `https://go.romdev-knowledge.workers.dev/<slug>`.
