1. HashMap для підрахунку частоти слів:
Тепер використовується HashMap для зберігання унікальних слів і їх частот, що значно знижує використання пам'яті.
2. Сортування за частотами: 
Замість вкладеного циклу тепер використовується сортування Map за значеннями (частотами), що є значно ефективнішим.
3. Зменшено використання рядкових операцій: 
Замість збірки рядків для унікальних слів та їх частот використовуються відповідні структури даних.