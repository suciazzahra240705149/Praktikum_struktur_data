# ✨ Pertemuan 1 – Queue & Stack di Python ✨

Struktur data **Queue** dan **Stack** adalah konsep dasar dalam ilmu komputer.  
Pada pertemuan ini kamu akan mempelajari cara kerja keduanya menggunakan Python.

---

## 🟦 Queue (Antrian)
Queue bekerja dengan prinsip **FIFO – First In First Out**.  
Artinya: *data yang pertama masuk adalah data yang pertama keluar.*

### 🔹 Kode Program
```python
queue = []

queue.append('A')
queue.append('B')
queue.append('C')
print("Queue: ", queue)

element = queue.pop(0)
print("Dequeue: ",element)

frontElement = queue[0]
print("peek: ", frontElement)

isEmpty = not bool(queue)
print("isEmpty: ", isEmpty)

print("size: ", len(queue))
```

### 🔍 Penjelasan
- `append()` → menambah data ke belakang queue  
- `pop(0)` → menghapus data paling depan  
- `queue[0]` → melihat elemen terdepan  
- `not bool(queue)` → cek apakah queue kosong  
- `len(queue)` → menghitung jumlah data  

---

## 🟩 Stack (Tumpukan)
Stack bekerja dengan prinsip **LIFO – Last In First Out**.  
Artinya: *data yang terakhir masuk adalah data yang pertama keluar.*

### 🔹 Kode Program
```python
stack = []

stack.append('A')
stack.append('B')
stack.append('C')
print("stack: ", stack)

element = stack.pop()
print("pop: ", element)

topElement = stack[-1]
print("peek: ", topElement)

isEmpty = not bool(stack)
print("isEmpty: ", isEmpty)

print("size: ",len(stack))
```

### 🔍 Penjelasan
- `append()` → push, menambah data ke atas stack  
- `pop()` → pop, mengambil data paling atas  
- `stack[-1]` → melihat data paling atas  
- `not bool(stack)` → cek apakah stack kosong  
- `len(stack)` → jumlah data pada stack  

---

> 📌 README ini sudah dirapikan dan dibuat aesthetic supaya mudah dibaca di GitHub.

