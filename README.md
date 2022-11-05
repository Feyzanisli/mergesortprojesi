# **Merge Sort Projesi**
*[patika.dev profilim için tıklayınız.](https://app.patika.dev/feyzameyza)*

**[ 6, 21, 11, 8, 12, 22 ]**  elemanlarının merge sort algoritmasına göre diziliş aşamaları şöyledir:
1. [ 6, 21, 11, 8, 12, 22 ]  
2. [ 6, 21, 11 ] / [8, 12, 22 ]
3. [ 6 ] / [21, 11 ] // [ 8 ] / [12, 22 ]
4. [ 6 ] / [ 21 ] // [ 11 ] /// [ 8 ] / [ 12 ] // [ 22 ]
5. [ 6 ] / [11 , 21] // [ 8 ] / [12, 22]
6. [ 6, 11, 21] / [8, 12, 22]
7. [ 6, 8, 11, 12, 21, 22]

---
Merge sort'un Big-O gösterimi;
eleman dizisi her seferinde bölünerek ilerlediğinden;
- 2^x=n yani log2n=x,
- domine eden logn olduğundan,
- **O(nlogn)**'dir.