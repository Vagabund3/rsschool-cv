# **Ruslan** **Lazarev**

####Junior Frontend Developer
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
