___

# GitHub commits activity analysis
Asliddin Tuxtasinov
___

Bu projrcetning maqsadi: 
- vaqt o'tishi bilan vaqt va vaqt oralig'idagi commitlar sonini analiysis qilish.

Ishlash tartibi:
- `get_owner_and_repoName` shu funksiya orqali github profile egasi va repository nomini ajratib olamiz.
- `get_github_commits_api_url` va bu fuksiya orqali esa github api url ni olamiz.
    - bu oddiy `https://api.github.com/repos/{owner}/{repo}/commits` shu apini qaytaradi.
- `get_commiter_and_message` bu funksiya orqali comitter haqida ma'lumot va commit messagedan tashkil topgan `json` data qaytaradi.

Project yakunida esa bizdagi datalarga asoslanib ikkita grafik qaytaradi:
- birinchisi vaqt va vaqt oralig'idagi commitlar soni orasidagi munosabat tasvirlovchi `chiziqli grafik`
- ikkinchisi vaqt va vaqt oralig'idagi commitlar soni orasidagi munosabat tasvirlovchi `issiqlik(heatmap) grafik`
