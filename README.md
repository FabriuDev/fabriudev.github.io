<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <header class="header">
        <h1 id="title" class="text-center">¿Cuanto sabes de Yesica Grigoli..?</h1>
        <p id="description" class="description text-center">
          Formulario hecho unicamente y especialmente para mi esposa...
        </p>
      </header>
      <form id="survey-form">
        <div class="form-group">
          <label id="name-label" for="name">Nombre completo</label>
          <input
            type="text"
            name="name"
            id="name"
            class="form-control"
            placeholder="ademas de princesa hermusa..."
            required
          />
        </div>
        <div class="form-group">
          <label id="email-label" for="date">¿Cuando este ser aparecio en el universo?</label>
          <input
            type="date"
            name="date"
            id="date"
            class="form-control"
            required
          />
        </div>
        <div class="form-group">
          <label id="number-label" for="number"
            >Edad<span class="clue">(muak)</span></label
          >
          <input
            type="number"
            name="age"
            id="number"
            min="10"
            max="99"
            class="form-control"
            placeholder="edad de mi amor?.."
          />
        </div>
        <div class="form-group">
          <p>¿Que cosas le encanta hacer?</p>
          <select id="dropdown" name="role" class="form-control" required>
            <option disabled selected value>Selecciona la correcta</option>
            <option value="student">Dibujar</option>
            <option value="job">Estar con su novio</option>
            <option value="learner">Comer pizza</option>
            <option value="preferNo">Hacer natacion</option>
            <option value="other">Todas son correctas</option>
          </select>
        </div>

        <div class="form-group">
          <p>¿Que la define mas?</p>
          <label>
            <input
              name="user-recommend"
              value="definitely"
              type="radio"
              class="input-radio"
              checked
            />Inteligencia</label
          >
          <label>
            <input
              name="user-recommend"
              value="maybe"
              type="radio"
              class="input-radio"
            />Belleza</label
          >

          <label
            ><input
              name="user-recommend"
              value="not-sure"
              type="radio"
              class="input-radio"
            />Educacion</label
          >
          <label
            ><input
              name="user-recommend"
              value="not-sure"
              type="radio"
              class="input-radio"
            />Unica</label
          >
          <label
            ><input
              name="user-recommend"
              value="not-sure"
              type="radio"
              class="input-radio"
            />Fidelidad</label
          >
          <label
            ><input
              name="user-recommend"
              value="not-sure"
              type="radio"
              class="input-radio"
            />Nada la define porque ella es Perfecta :)...</label
          >
        </div>

        <div class="form-group">
          <p>¿Cual es la comida preferida de Yesi?</p>
          <select id="most-like" name="mostLike" class="form-control" required>
            <option disabled selected value>Selecciona una opcion</option>
            <option value="challenges">Pastas</option>
            <option value="projects">Hamburguesas</option>
            <option value="community">Pizzas</option>
            <option value="openSource">el pito de fabri</option>
          </select>
        </div>

        <div class="form-group">
          <p>
            ¿Que le gustaria ser a Yesi?
            <span class="clue">(te amu <3)</span>
          </p>

          <label
            ><input
              name="prefer"
              value="front-end-projects"
              type="checkbox"
              class="input-checkbox"
            />Psicologa</label
          >
          <label>
            <input
              name="prefer"
              value="back-end-projects"
              type="checkbox"
              class="input-checkbox"
            />Nadadora</label
          >
          <label
            ><input
              name="prefer"
              value="data-visualization"
              type="checkbox"
              class="input-checkbox"
            />esposa de fabri</label
          >
          <label
            ><input
              name="prefer"
              value="challenges"
              type="checkbox"
              class="input-checkbox"
            />Todas son correctas</label>
        </div>

        <div class="form-group">
          <p>Si falto algo sobre yesi, decilo por aca!</p>
          <textarea
            id="comments"
            class="input-textarea"
            name="comment"
            placeholder="muchos muaks..."
          ></textarea>
        </div>

        <div class="form-group">
          <button type="submit" id="submit" class="submit-button">
            Enviar <3
          </button>
        </div>
      </form>
    </div>
  </body>
</html>
