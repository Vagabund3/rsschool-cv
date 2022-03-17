# **Ruslan** **Lazarev**

#### Junior Frontend Developer

---

## _Contact information_

**Country:** Russian Federation

**Town:** Novorossyisk

**Email:** rus231997@gmail.com

[**GitHub**](https://github.com/Vagabund3)

**Discord:** Ruslan Lazarev (@vagabund3)

---

## _Code example_

[Training project on React JS](https://github.com/Vagabund3/React-project)

Login form:

```
const LoginForm = ({ handleSubmit, error, captchaUrl }) => {
  return (
    <form onSubmit={handleSubmit}>
      {createField("Email", "email", [required], Input)}
      {createField("Password", "password", [required], Input, {
        type: "password",
      })}
      {createField(
        null,
        "rememberMe",
        [],
        Input,
        { type: "checkbox" },
        "remember me"
      )}

      {/* если captchaUrl присутствует то показыв. картинку */}
      {captchaUrl && <img src={captchaUrl} />}
      {/* field для captcha */}
      {captchaUrl && createField("Symbols from image", "captcha",
      [required],Input, {})}

      {/* //показываем props.error только тогда когда есть ошибка */}
      {error && <div className={style.formSummaryError}>{error}</div>}
      <div>
        <button>Login</button>
      </div>
    </form>
  );
};
```

---

## _Experience_

Intern frontend-developer: 2021-05-10 – 2021-08-20
ChatKeeperBot: Worked on creating an editor for a chat bot based on modular framework for visual programming: rete.js.

---

## _Courses_

| Date                    |                                                               Completed courses |
| :---------------------- | ------------------------------------------------------------------------------: |
| 2020-02-01 – 2019-03-01 | [JavaScript algorithms and data structures](https://www.freecodecamp.org/learn) |
| 2019-08-10 – 2019-08-19 |         [HTML Basics](https://www.sololearn.com/Certificate/1024-14160181/jpg/) |
| 2020-03-15 – 2020-03-21 |          [CSS Basics](https://www.sololearn.com/Certificate/1023-14160181/jpg/) |
| 2020-04-10 – 2020-04-24 |           [JS Basics](https://www.sololearn.com/Certificate/1024-14160181/jpg/) |

---

## _Languages_

**English**: A2/B1

---

## _Programming Languages and skills_

HTML, CSS, JS, experience with Git and its environment, understanding Browser Client Interaction:(HTTP request), AJAX requests. I spend a lot of time learning React applying it in the development of educational project. Also had experience with Vue.JS during internship.
I try to write clean and readable code with comments. I can solve problems - I can google, quickly find suitable solutions and apply them.
