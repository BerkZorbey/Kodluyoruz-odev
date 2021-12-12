### Merge Sort

**[16,21,11,8,12,22]**  **n** -> Merge Sort

**1.** Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

**1.** [16,21,11,8,12,22] ***n***

**2.** [16,21,11] --- [8,12,22] ***n***

**3.** [16,21] [11] --- [8,12] [22] ***n***

**4.** [11,16,21] --- [8,12,22] ***n***

**5.**  [8,11,12,16,21,22] ***n***

---

**2.** Big-O gösterimini yazınız.

2^x=n (Toplam işlem sayısı)
x=logn

[O(logn)(işlem sayısı)] x [O(n)(her işlemde)]

=**Big O(nlogn)**