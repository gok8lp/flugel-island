# FLUGEL Island: ortak ajan kuralları

- Asıl geliştirme kaynağı aynı PC'deki `../flugel/extensions/flugel-island@flugel/`; bu depo yayınlanan ayrı kopyadır. İki repo arasında senkronizasyon öncesi `git status` ve dosya diff'ini kontrol et. `rsync --delete` gibi işlemlerle başka ajanın çalışmasını ezme.
- Ortak Codex/Claude panosu ana depoda `../flugel/.ai_workspace/AGENT_TASK_BOARD.md`, kurallar `../flugel/.ai_workspace/RULES_AND_PERMISSIONS.md`, giriş `../flugel/.ai_workspace/README.md`. Aynı PC'de işe başlamadan görev sahiplen; koddan sonra test ve commit kanıtını yaz.
- `npm run lint` ve `npm test` ile ilgili değişikliği doğrula; GNOME etkileşimini etkileyen değişiklikte uygun başsız testi de çalıştır. Kullanıcıya görünen metinler çevrilebilir ve karanlık tema korunur.
- `/home/flugel/Projects/weekly-task` ve `/home/flugel/Projects/weekly-tasks` dizinlerine okuma, düzenleme, test, commit, push veya otomasyonla dokunma.
- Commit/push öncesinde uzak dalı ve iki eklenti kopyasının eşitliğini kontrol et. Yeni sürüm etiketi kullanıcı isteğiyle yapılır.
