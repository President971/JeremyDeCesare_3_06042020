P3_decesare_jeremy

Le coeur' de boeuf

HTML:
        <div class="coeur">
                
                <h3>Le coeur de Boeuf</h3>
                <i class="fas fa-heart"></i>
                
        </div>


CSS:
		.coeur .fas{
			position: relative;
			float: right;
			right: 20px;
			top: -20px;
			font-size: 21px;
			-webkit-text-fill-color: white;
			-webkit-text-stroke-width: 1px;
			-webkit-text-stroke-color: black;
		}
		.coeur .fas:hover{
			background: linear-gradient(#FF79DA, #9356DC);
			-webkit-background-clip: text;
			-webkit-text-fill-color: transparent;
			-webkit-text-stroke-width: 0;
			transition: 500ms;
		}
