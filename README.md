# week1_assignment
GitHub par code push karne ke liye aapko pehle ek online repository banani hogi aur phir terminal (ya VS Code) se kuch Git commands chalani hongi.

1. Pehli Dafa Naya Project Push Karne Ka Tarika

• GitHub par Repository banayein. Apne GitHub account mein login karein, upar + icon par click karke New repository select karein, project ka naam likhein aur Create repository par click karke uska HTTPS link copy kar lein.
• Apne Project folder mein Terminal kholein. Apne computer par project ke folder mein jayein aur Terminal ya VS Code terminal open karein.
• Git ko initialize karein. Folder ko Git ke liye taiyar karne ke liye yeh command chalayein:bash
git init
Use code with caution.
• Files ko stage aur commit karein. Tamam files ko select karne aur save karne ke liye yeh do commands chalayein:bash
git add .
git commit -m "First commit"
Use code with caution.
• Branch set karein aur GitHub se link karein. Apni main branch set karein aur copy kiya hua GitHub link jodein:bash
git branch -M main
git remote add origin <yahan-apna-repository-link-paste-karein>
Use code with caution.
• Code push karein. Aakhir mein apna code upload karne ke liye yeh command likhein:bash
git push -u origin main
Use code with caution.

2. Jab Code Mein Koi Nayi Tabdeeli (Changes) Push Karni Ho

Agar aap pehle hi project push kar chuke hain aur ab naya code update karna chahte hain, toh sirf yeh teen commands chalayein:
• Files add karein. Nayi ya tabdeel shuda files ko add karein.bash
git add .
Use code with caution.
• Commit message likhein. Tabdeeli ke bare mein chhota sa message likh kar save karein.bash
git commit -m "Code updated"
Use code with caution.
• Push karein. Apne local changes ko GitHub par bhej dein.bash
git push origin main
Use code with caution.

Zaroori Tips

• Git Install hona zaroori hai. Agar yeh commands kaam na karein, toh check karein ke aapke system mein Git install hai ya nahi.
• Login Prompt. Pehli baar git push chalane par browser mein GitHub login ki window khulegi, wahan sign in karke permission dein.
• Bina Commands ke Push. Agar aap commands nahi likhna chahte, toh aap GitHub Desktop app ya VS Code ke Source Control tab ka istemal karke sirf ek click se bhi code push kar sakte hain. Mukammal tafseelat ke liye aap GitHub Docs bhi dekh sakte hain.
