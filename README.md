# 🥳 React JS Hooks 🥳

| Basic Hooks | Additional Hooks    | Library Hooks        |
| ----------- | ------------------- | -------------------- |
| useState    | useReducer          | useSyncExternalStore |
| useEffect   | useCallback         | useInsertionEffect   |
| useContext  | useMemo             |                      |
|             | useRef              |                      |
|             | useImperativeHandle |                      |
|             | useLayoutEffect     |                      |
|             | useDebugValue       |                      |
|             | useDeferredValue    |                      |
|             | useTransition       |                      |
|             | useId               |                      |

##### Basic Hooks 😇

1. useState

- Pengertian : Digunakan untuk menampung data. ini sebenarnya sama seperti sebuah variabel, dimana kita memiliki sebuah nilai awal kemudian kita bisa merubah nilai yang ada di variabel tersebut
- Deklarasi : `const [nama, setNama] = useState("Nama Kamu")`
- Mengambil Data : `<h1>{nama}</h1>`
- Mengubah Nilai : `setNama("Nama Baru Kamu")`

2. useEffect

- Pengertian : Sebuah Hooks yang akan di jalankan pertama kali ketika halaman di render yang di dalam useEffect kita bisa menjalankan berbagai perintah. useEffect juga bisa berjalan ketika di beri sebuah trigger untuk menjalankan useEffect tersebut.
- Deklarasi : `useEffect(() => { // kode kamu return () => { // mengembalikan semua data ke semula } }[trigger jika useEffect ingin di jalankan lagi sesuai kondisi yang telah kita tentukan ])`
