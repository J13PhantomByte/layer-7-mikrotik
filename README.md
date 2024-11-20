-LANGKAH LANGKAH MEMBUAT LAYER 7 PROTOKOL DI MIKROTIK
> 1. Masuk ke Firewall dan klik Layer 7
> 2. Beri nama contoh -> Blokir Linux dan ubuntu
> 3. lalu masukkan code dibawah ini  
>    
```bash
	^.+(linux.org|ubuntu.com).*$
    ```
    
> 4. Lalu klik Filter rules 
> 5. Chain -> Forward | Advanced -> Pilih layer 7 | Action -> Drop
> 6. selesai
