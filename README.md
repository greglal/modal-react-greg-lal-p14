# HRnet modal for P14-wealth health project

This is a reusable react modal, developed during 14th front-end developer training project

## installation

```bash
npm i modal-react-greg-lal-p14
```

## How it works?

1. import the plugin inyour project :

```bash
import Modal from "modal-react-greg-lal-p14"
```

2. render it in your component

```bash
< >
  <Modal />
< />
```

3. modify the style

```bash
.modal{
    width: 100%;
    height: 100%;
    /*background-color: red;*/
    position: absolute;
    top: 0;
    left: 0
}

.modal-content{
    position: absolute;
    top: 50%;
    right: 40%;
    display: flex;
    flex-direction: row-reverse;
    justify-content:space-between;
    width: 400px;
    height: 60px;
    background-color: #93AD18;
    border-radius: 15px;
    box-shadow: 2px 2px #5A6F06;
}

.modal-close-icon{
    margin: 5px 15px;
}

.message{
    margin:auto;
    align-self: center;
}
```
