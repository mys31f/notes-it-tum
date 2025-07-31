
```flow
meta=>operation: Metamodel
framework=>operation: EA Framework
model=>operation: Model
eamodel=>operation: EA model
architecture=>operation: Architecture
ea=>operation: EA
system=>operation: System
ecosystem=>operation: Enterprise‑wide digital ecosystem

meta->model: Is a manual for
framework->eamodel: Is a manual for

framework->meta: Is a
eamodel->model: Is a

model->architecture: Represents
eamodel->ea: Represents

architecture->system: Has an
ea->ecosystem: Has an

system->ecosystem: Is a
```