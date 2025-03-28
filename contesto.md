# c4
@startuml
!include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml

Person(userAlias, "Usuário", "Alunos")
Person(teachAlias, "Professor", "Professores")
Person(adminAlias, "Administrador", "Gestor")
System(systemAlias, "Sistema", "Site")

Rel(userAlias, systemAlias,)
Rel(teachAlias, systemAlias,)
Rel(adminAlias, systemAlias,)
@enduml
