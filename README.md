def shell_sort(arr):
    n = len(arr)
    gap = n // 2

    while gap > 0:
        for i in range(gap, n):
            temp = arr[i]
            j = i
            while j >= gap and arr[j - gap] > temp:
                arr[j] = arr[j - gap]
                j -= gap
            arr[j] = temp
        gap //= 2

if _name_ == "_main_":
    # Lista de números desordenados
    numeros = [12, 34, 54, 2, 3]

    print("Lista antes de ordenar:", numeros)
    
    shell_sort(numeros)
    
    print("Lista después de ordenar:", numeros)- 👋 Hi, I’m @Marthabarria
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Marthabarria/Marthabarria is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
