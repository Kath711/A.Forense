# A.Forense

<img width="1920" height="1200" alt="Screenshot from 2026-11-18 23-01-25" src="https://github.com/user-attachments/assets/c7f091c2-7481-448b-9aa0-75fabe0c08f1" />




wget https://github.com/Velocidex/velociraptor/releases/download/v0.77.3/velociraptor-v0.77.3-linux-amd64.gz

gunzip velociraptor-v0.77.3-linux-amd64.gz

mv velociraptor-v0.77.3-linux-amd64 velociraptor
chmod +x velociraptor

./velociraptor version

./velociraptor gui
kathia@kathia-ThinkPad-X1-Carbon-Gen-9:~/Velociraptor$ wget https://github.com/Velocidex/velociraptor/releases/download/v0.77.3/velociraptor-v0.77.3-linux-amd64.gz
--2026-11-19 12:42:14--  https://github.com/Velocidex/velociraptor/releases/download/v0.77.3/velociraptor-v0.77.3-linux-amd64.gz
Resolving github.com (github.com)... 140.82.114.3
Connecting to github.com (github.com)|140.82.114.3|:443... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://release-assets.githubusercontent.com/github-production-release-asset/126576769/4fcb32ad-0b52-4dc3-be85-bca45899b830?sp=r&sv=2018-11-09&sr=b&spr=https&se=2026-11-19T19%3A21%3A52Z&rscd=attachment%3B+filename%3Dvelociraptor-v0.77.3-linux-amd64.gz&rsct=application%2Foctet-stream&skoid=96c2d410-5711-43a1-aedd-ab1947aa7ab0&sktid=398a6654-997b-47e9-b12b-9515b896b4de&skt=2026-11-19T18%3A20%3A56Z&ske=2026-11-19T19%3A21%3A52Z&sks=b&skv=2018-11-09&sig=DjvqIYlMjZVaUfceepQ%2F2w53SqkuhUbWLqKNlfAQcSY%3D&jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmVsZWFzZS1hc3NldHMuZ2l0aHVidXNlcmNvbnRlbnQuY29tIiwia2V5Ijoia2V5MSIsImV4cCI6MTc5NTExNTUzNCwibmJmIjoxNzk1MTEzNzM0LCJwYXRoIjoicmVsZWFzZWFzc2V0cHJvZHVjdGlvbi5ibG9iLmNvcmUud2luZG93cy5uZXQifQ.rqODjZm0ECOQd2sKoYupk009sFqc7nnX-IK9xPgKsiE&response-content-disposition=attachment%3B%20filename%3Dvelociraptor-v0.77.3-linux-amd64.gz&response-content-type=application%2Foctet-stream [following]
--2026-11-19 12:42:14--  https://release-assets.githubusercontent.com/github-production-release-asset/126576769/4fcb32ad-0b52-4dc3-be85-bca45899b830?sp=r&sv=2018-11-09&sr=b&spr=https&se=2026-11-19T19%3A21%3A52Z&rscd=attachment%3B+filename%3Dvelociraptor-v0.77.3-linux-amd64.gz&rsct=application%2Foctet-stream&skoid=96c2d410-5711-43a1-aedd-ab1947aa7ab0&sktid=398a6654-997b-47e9-b12b-9515b896b4de&skt=2026-11-19T18%3A20%3A56Z&ske=2026-11-19T19%3A21%3A52Z&sks=b&skv=2018-11-09&sig=DjvqIYlMjZVaUfceepQ%2F2w53SqkuhUbWLqKNlfAQcSY%3D&jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmVsZWFzZS1hc3NldHMuZ2l0aHVidXNlcmNvbnRlbnQuY29tIiwia2V5Ijoia2V5MSIsImV4cCI6MTc5NTExNTUzNCwibmJmIjoxNzk1MTEzNzM0LCJwYXRoIjoicmVsZWFzZWFzc2V0cHJvZHVjdGlvbi5ibG9iLmNvcmUud2luZG93cy5uZXQifQ.rqODjZm0ECOQd2sKoYupk009sFqc7nnX-IK9xPgKsiE&response-content-disposition=attachment%3B%20filename%3Dvelociraptor-v0.77.3-linux-amd64.gz&response-content-type=application%2Foctet-stream
Resolving release-assets.githubusercontent.com (release-assets.githubusercontent.com)... 185.199.108.133, 185.199.111.133, 185.199.109.133, ...
Connecting to release-assets.githubusercontent.com (release-assets.githubusercontent.com)|185.199.108.133|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 30350671 (29M) [application/octet-stream]
Saving to: ‘velociraptor-v0.77.3-linux-amd64.gz’

velociraptor-v0.77. 100%[===================>]  28.94M  66.4MB/s    in 0.4s    

2026-11-19 12:42:14 (66.4 MB/s) - ‘velociraptor-v0.77.3-linux-amd64.gz’ saved [30350671/30350671]

kathia@kathia-ThinkPad-X1-Carbon-Gen-9:~/Velociraptor$ gunzip velociraptor-v0.77.3-linux-amd64.gz
kathia@kathia-ThinkPad-X1-Carbon-Gen-9:~/Velociraptor$ mv velociraptor-v0.77.3-linux-amd64 velociraptor chmod +x velociraptor
mv: target 'velociraptor': No such file or directory
kathia@kathia-ThinkPad-X1-Carbon-Gen-9:~/Velociraptor$ mv velociraptor-v0.77.3-linux-amd64 velociraptor chmod +x Velociraptor
mv: target 'Velociraptor': No such file or directory
kathia@kathia-ThinkPad-X1-Carbon-Gen-9:~/Velociraptor$ 





