- 👋 Hi, I’m @Sendut17
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Sendut17/Sendut17 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
docker build -t dev-reward-script .

docker run -it -v ~/.ssh:/root/.ssh dev-reward-script
./install.sh

python3 -m venv claim-venv

source claim-venv/bin/activate

pip3 install -r python/requirements.txt

python3 python/proof.py

For bash script:
./install.sh

./proof-sh/proof.sh
