``` python
class Bio:
    def __init__(self):
        self.past_role = "Data Scientist"
        self.current_role = "AI Engineer (for now)"
        self.future_focus = "Cloud & Data"
        self.fun_fact = "I kill XAUUSD on the Daily"
        self.email = "benedictdebrah.o@gmail.com"

    def __str__(self):
        return f"""

🚀 Swallowing the Hard Pill  

👨‍💻 Previously: {self.past_role}  
🔄 Currently: {self.current_role}  
🌍 Future: {self.future_focus}  
💰 Fun fact: {self.fun_fact}  

🔎 Always learning, adapting, and building for what's next.  
📩 **Contact:** {self.email}  
        """.strip()


print(Bio())

```
