---
name: hardware-sourcing-design
description: Make hardware design and component decisions around verified availability in Korea, China or Japan, using Korean, Chinese and Japanese searches. Apply when selecting or substituting mechanical or electronic parts, materials, fasteners, tools or fabrication processes, and before committing their interfaces to CAD, a BOM or a print handoff.
---

# Design around obtainable hardware

Availability is a design input, not a shopping task postponed until after CAD. Do not make development depend on an obscure catalogue part before establishing a practical Korea/China/Japan supply route. This applies to newly selected parts and changed interfaces; it does not require requalifying unrelated existing hardware on every task.

## Start with functional needs and actual inventory

Check what the user owns, has ordered and can reuse. Keep received, ordered, merely recommended and unknown stock separate. Define the required function, load, motion, size envelope, interfaces and tolerances before selecting a brand or part number. Separate essential constraints from adjustable design choices. Exact dimensions from a previous catalogue choice are not automatically essential requirements.

## Source before fixing interfaces

Follow this sourcing order: Korea → China → Japan → HyperFlight UK or broader global search. Search Korea first using Korean queries and Korean supplier pages. If suitable options are unavailable or impractical, search China using Simplified Chinese queries and supplier pages; if that route is also unsuitable, search Japan using Japanese queries and supplier pages. Move to HyperFlight UK or a broader global search only after these regional options are exhausted or shown impractical. Assess each route on availability, total landed cost and delivery time to the user. Keep exact model numbers unchanged while translating component names, dimensions and technical attributes. English-only queries or translated English search results do not satisfy this step.

Use specific native terms and synonyms, for example:
- Torsion spring: 토션 스프링 / 비틀림 스프링; 扭簧 / 扭转弹簧; トーションばね / ねじりばね.
- Wire diameter, outside diameter, winding: 선경, 외경, 좌권/왼쪽 감김; 线径, 外径, 左旋; 線径, 外径, 左巻き.
- In stock, small quantity, custom: 재고, 소량, 주문제작; 现货, 小批量, 定制; 在庫, 小ロット, 特注.

Choose relevant local channels:
- Korea: Coupang, Naver Shopping and MISUMI Korea; [DeviceMart / 디바이스마트](https://www.devicemart.co.kr/) for electronics and tools; [Falconshop / 팰콘샵](https://www.falconshop.co.kr/) for RC hardware, servos and fasteners; [Compuzone / 컴퓨존](https://www.compuzone.co.kr/) for electronics, adapters and connectors; DNS Tech / 디엔에스테크 through its [Coupang shop](https://shop.coupang.com/vid/A00068792) for wiring and related supplies (verify the seller and exact option). Include relevant local manufacturers/distributors.
- China: [JD / 京东](https://www.jd.com/) for general retail, tools and power supplies; [Taobao / 淘宝](https://www.taobao.com/) and [Tmall / 天猫](https://www.tmall.com/) for broad seller selection and miscellaneous hardware; [MISUMI China / 米思米](https://www.misumi.com.cn/) for dimensioned mechanical parts, springs, fasteners and linear guides; [LCSC / 立创商城](https://www.szlcsc.com/) for electronic components, connectors, modules and development boards; [1688 / 阿里巴巴1688](https://www.1688.com/) for wholesale and manufacturer sourcing, checking minimum order quantities.

- Japan: [Amazon Japan](https://www.amazon.co.jp/) and [Rakuten Ichiba / 楽天市場](https://www.rakuten.co.jp/) for general marketplace sourcing, comparable to Coupang/Naver Shopping; [MISUMI Japan / ミスミ](https://jp.misumi-ec.com/) for dimensioned mechanical parts; [Marutsu / マルツ](https://www.marutsu.co.jp/), [Akizuki Denshi / 秋月電子通商](https://akizukidenshi.com/) and [Sengoku / 千石電商](https://www.sengoku.co.jp/) for electronics, modules, connectors and wiring, comparable to DeviceMart; [MonotaRO / モノタロウ](https://www.monotaro.com/) for tools and industrial consumables; [Super Rajikon / スーパーラジコン](https://www.super-rc.co.jp/rc/) for RC hardware, comparable to Falconshop. These are sourcing channels, not proof of stock or shipping to Korea.
- Outside-region fallback: use a broader global search or [HyperFlight](https://www.hyperflight.co.uk/) in the United Kingdom for RC servos and accessories. Use either only after checking Korea, then China, then Japan and finding no practical suitable option. Explain why the regional routes fail and verify stock, shipping to Korea, total landed cost and delivery time. This does not require searching every listed shop for every component.

Search results are leads, not compatibility evidence. Do not assume a Korean website means domestic stock or a Chinese/Japanese listing can ship to the user. Distinguish domestic delivery within China or Japan from delivery to Korea; verify direct shipping or forwarding, total delivery time and landed cost before treating a regional option as obtainable.

Inspect the exact selectable variant and seller, not just the product-family title. Read technical details and dimensioned images, using browser tools when the text extraction omits them. Prefer manufacturer documentation for performance claims. Establish:
- Exact option/model, supplier and direct link; date checked.
- Material, dimensions and the performance characteristics relevant to the mechanism.
- Stock or made-to-order status, minimum quantity, price and delivery to the user's location when available.
- Domestic stock versus overseas import; any unconfirmed shipping route or lead time.

Label missing information explicitly. A catalogue entry proves existence, not stock. A custom manufacturer is a quotation lead until capability, quantity and delivery are confirmed. Never present a seller-contact link as an approved product to buy.

## Let available parts shape the design

Compare feasible sourced candidates against functional requirements. Prefer common stocked components, existing tools/fasteners and small order quantities over exact nominal matches that are hard to obtain. Consider total landed cost, delivery, replacement availability and redesign effort alongside engineering performance.

When a sourced part differs, assess whether changing its mount, clearance, preload or other adjustable parameter preserves function. Check coupled effects before approving it: for example, a spring's wire size alone does not establish torque, permitted deflection, loaded coil clearance or reset behavior. Do not reject every alternative merely because it differs from the first catalogue choice, and do not declare one equivalent solely from appearance or size.

Before freezing a new dependent CAD interface, BOM choice or fabrication handoff, have both a technically justified component selection and credible current Korea/China/Japan availability evidence for the required quantity. Refresh availability when preparing the purchase or handoff; old evidence may no longer apply. Physical validation can remain outstanding if clearly identified as the purpose of a prototype.

If no suitable part is verified, keep the interface provisional. Continue independent work and resolve the dependency by assessing another locally obtainable component, an adjustable interface, or a documented custom quote. Clearly flag affected print files before they are sent. Do not turn uncertainty into a blanket halt on development, silently remove required functionality, or claim an unverified substitute is ready to purchase. Present an outside-region option only as an explicit fallback when Korea/China/Japan sourcing cannot be established.

## Leave a usable decision record

For consequential choices, save a short sourcing/selection note in the project: functional requirements, selected exact variant and link, availability evidence/date, unresolved details, required interface changes and relevant validation. Distinguish sourcing confidence from engineering confidence. Update the BOM and affected handoff instructions when a selection changes, preserving historical versions.

Report the chosen option and why it is practical; make any remaining supplier question specific and actionable. Draft native-language supplier enquiries when needed. Searching and drafting do not authorize sending messages, placing orders or commissioning work.
