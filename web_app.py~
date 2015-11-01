from flask import Flask,render_template 
app=Flask(__name__)

@app.route("/home")
def hello():
	return render_template("home.html")


@app.route("/contactMe")
def hey():
	return render_template("contactMe.html")

@app.route("/AboutMe")
def hi():
	return render_template("AboutMe.html")

if __name__ == "__main__":
	app.run()
