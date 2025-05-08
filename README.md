# Nach dem Zurücksetzen: Neu erzeugen der README.md-Datei mit dem angegebenen Inhalt

readme_content = """
# 👋 Hallo, ich bin @danijel

👀 Ich interessiere mich für Softwarearchitektur, sauberen Code, skalierbare Systeme – und die tiefgreifende Interaktion zwischen Mensch und KI.  
🌱 Aktuell lerne ich fortgeschrittene DevOps-Praktiken, verteilter Datenbankentwurf – und arbeite intensiv daran, ein Prompt-Master zu werden.  
🤖 Ich programmiere KI-Systeme, binde sie an bestehende Infrastrukturen an und entwickle intelligente Schnittstellen zwischen Daten und Dialog.  
💞️ Ich suche nach Projekten zur Zusammenarbeit im Bereich KI, Backend-Architektur und Open Source – besonders mit Python, Go oder Rust.  
📫 Du erreichst mich unter: xxjokic01@gmail.com  
😄 Pronomen: er/ihm  
⚡ Fun Fact: Ich habe mit dem Programmieren in einem lauten Café auf einem geliehenen Laptop angefangen – heute orchestriere ich KI-Systeme in der Cloud.

<!---
is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
""".strip()

# Speichern als README.md
readme_file_path = "/mnt/data/README.md"
with open(readme_file_path, "w") as file:
    file.write(readme_content)

readme_file_path
