# Guides
Personal guides for development
## Structure of Angular 2 App
```
/ng2-app
  /app
    /people
      people.module
      people.component
      peopleList.component
      /profile
        profile.component
    /contacts
      contacts.module
      contactList.component
      contactDetail.component
    app.component
    app.module
```
## Data Binding

<table>
  <thead>
    <tr>
      <td>Data direction</td>
      <td>Syntax</td>
      <td>Binding type</td>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>One-way from data source to view target</td>
    <td>{{expression}} [target] = "expression" bind-target = "expression"</td>
    <td>Interpolation <br> Property <br> Attribute <br> Class <br> Style</td>
    </tr>
  </tbody>
</table>
