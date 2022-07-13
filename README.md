# goiteens-homework-posicion


 <div class="backdrop is-hidden " >

        <div class="modal " data-modal  >
            <button type="button" class="modal-button" data-modal-close></button>
        </div>
    </div>
    .backdrop{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,  0, 0, 0.2);
    opacity: 1;
    

}
.modal{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 581px;
    height: 528px;
    background-color: #F5F4FA;
    opacity: 1;
    
    
     
}
.modal-button{
    position: absolute;
    top: 8px;
    right: 8px;
    width: 30px;
    height: 30px;
    background-image: url(./img/icons/close.svg);
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 50%;
    background-size: contain;

}
.backdrop .is-hidden{

    opacity: 0;
    pointer-events: none;
}