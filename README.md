const me = {
  name: "Serhii",
  focus: ["Bootstrap", "HTML", "CSS", "JavaScript"],
  languages: ["English", "German"],
  interests: ["Programming", "Language Learning", "Web Development"],

  introduce() {
    console.log(`Hi, I'm ${this.name}`);
    console.log(`I'm working with ${this.focus.join(", ")}`);
    console.log(`Languages I know: ${this.languages.join(", ")}`);
    console.log(`Interests: ${this.interests.join(", ")}`);
  }
};

me.introduce();
