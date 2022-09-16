# ParkourClimb ORIGINAL CSS BACKUP

body{
	padding: 0;
	margin: 0;
}
iframe{
	position: fixed;
    top: 0px;
    bottom: 0px;
    right: 0px;
    width: 100%;
    border: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    z-index: 100;
    height: 100%;
}
.Back{
	position: relative;
	padding:1rem 2rem;
	top: -30px;
	right: 0.2rem;
	border-radius: 1rem;
	background-color:white;
	outline: none;
	font-size: medium;
	margin-bottom: 1rem;
	border: none;
	transition: background-color,border-radius,border 0.75s ease-in-out;
	transition: color 0.30s ease-in-out;
    z-index: 300;
}
.Back:hover{
	background-color:red;
	color:white;
	border: 1px solid black;
	border-radius: 2rem;
	cursor: pointer;
} 
