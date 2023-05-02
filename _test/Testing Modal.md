---
title: Testing Modal
permalink: /permalink/
description: ""
---
<style>
.modal-window {
      position: fixed;
      background-color: rgba(200, 200, 200, 0.75);
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;
      z-index: 999;
      opacity: 0;
      pointer-events: none;
      
    }
    
.modal-window:target {
      opacity: 1;
      pointer-events: auto;
    }
    
.modal-window > div {
      width: 80%;
			height: 60%;
      position: relative;
      margin: 10% auto;
      padding: 2rem;
      background: #fff;
      color: #444;
    }
    
.modal-window header {
      font-weight: bold;
    }
    
.modal-close {
      color: #aaa;
      line-height: 50px;
      font-size: 80%;
      position: absolute;
      right: 0;
      text-align: center;
      top: 0;
      width: 70px;
      text-decoration: none;
    }
    
.modal-close:hover {
      color: #000;
    }
    
.modal-window h1 {
      font-size: 150%;
      margin: 0 0 15px;
    }

</style>



<h3>This is a testing page</h3>

   <a href="#open-modal">Open Modal</a>
  
<div class="modal-window" id="open-modal">

   <div>
        <a class="modal-close" title="Close" href="#modal-close">close ×</a>
        <h1>CSS Modal</h1>
        <div>The quick brown fox jumped over the lazy dog.</div>
      </div>
    </div>