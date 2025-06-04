class DataScientist:
    def __init__(self, full_name="Rendika Nurhartanto Suharto", nickname="Rendika", role="Data Scientist", languages_spoken=["id_ID", "en_US"], university="Telkom University Surabaya", status="Undergraduate Student"):
        self.full_name = full_name
        self.nickname = nickname
        self.role = role
        self.languages_spoken = languages_spoken
        self.university = university
        self.status = status

    def say_hi(self):
        print(f"Hi! I'm {self.nickname} ({self.full_name}), a {self.role}.")
        print(f"I can engage in a conversation with you using these languages: {', '.join(self.languages_spoken)}")
        print(f"I am currently studying at {self.university} as an {self.status}.")
        print("Hope you find something interesting here!")

def main():
    me = DataScientist()
    me.say_hi()

if __name__ == "__main__":
    main()
