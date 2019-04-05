# Membatalkan Sales Order

## A. INPUT

* Data sales order yang akan dibatalkan harus memiliki status (1) **Draft Quotation**, atau (2) **Sales Order**, atau (3) **Sale To Invoice**

![](../../img/sales-order/status-sales-order.png)

![](../../img/sales-order/status-sales-to-invoice.png)

* User yang akan membatalkan harus memiliki akses untuk membatalkan sales order.

## B. LANGKAH KERJA

1. Buka menu **Sales -> Sales -> All Orders**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data sales order yang akan dibatalkan. Abaikan jika data sudah dibuka.
3. Klik tombol **Cancel Quotation** atau **Cancel Order** pada bagian atas-kiri form.

![](../../img/sales-order/tombol-cancel.png)

![](../../img/sales-order/tombol-cancel-order.png)

Pop-up **Reason for Cancellation** akan muncul

![](../../img/sales-order/pop-up-cancel-reason.png)

4. Pilih **Reason** sesuai dengan alasan pembatalan
5. Klik tombol **Confirm** pada bagian bawah-kiri pop-up **Reason for Cancellation**

![](../../img/sales-order/tombol-confirm-cancel.png)

## C. OUTPUT

* Status dari sales order akan berubah menjadi **Cancelled**

![](../../img/sales-order/status-cancelled.png)

* Isian sales order sudah tidak bisa diubah
