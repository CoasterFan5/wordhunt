<div class="wrap">
	<div class="grid">
		<div class="letter styleize">L</div>
		<div class="letter styleize">S</div>
		<div class="letter styleize">T</div>
		<div class="letter styleize">A</div>
		<div class="letter styleize">W</div>
		<div class="letter styleize">O</div>
		<div class="letter styleize">R</div>
		<div class="letter styleize">D</div>
		<div class="letter styleize">H</div>
		<div class="letter styleize">U</div>
		<div class="letter styleize">N</div>
		<div class="letter styleize">T</div>
		<div class="letter styleize">P</div>
		<div class="letter styleize">D</div>
		<div class="letter styleize">O</div>
		<div class="letter styleize">A</div>
	</div>
	<div class="join">
		<input class="input styleize" href="/" placeholder="Enter Code" />
		<button class="button styleize">Join Lobby</button>
	</div>
</div>

<style>
	.wrap {
		width: 100%;
		height: 100vh;
		background: #f1f1f1;
		display: flex;
		align-items: center;
		flex-direction: column;
	}
	.grid {
		height: 70vh;
        margin-top: 50px;
		min-width: 400px;
		aspect-ratio: 1/1;
		display: grid;
		grid-template-columns: repeat(4, 1fr);
		column-gap: 10px;
		row-gap: 1em;
	}
    .join {
        width: 70vh;
		margin-top: 50px;
		box-sizing: border-box;
		min-width: 400px;
		display: flex;
		flex-direction: row;
	}
	.input {
		all: unset;
		background: rgb(172, 172, 172);
		width: 100%;
		font-size: 2rem;
        padding: 10px;
		padding-right: 20px;
		box-sizing: border-box;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.button {
		all: unset;
        outline: 0px;
		background: rgb(172, 172, 172);
		height: 100%;
		width: 100%;
		margin-left: 10px;
		font-size: 2rem;
        padding: 10px;
        padding-right: 20px;
        margin-right: 0px;
        box-sizing: border-box;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.letter {
		width: 100%;
		height: 100%;
		font-size: 3rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
    .styleize {
        background: rgb(172, 172, 172);
        border-radius: 5px;
        box-shadow: 3px 3px rgba(0, 0, 0, 0.6);
		transition: all cubic-bezier(0.075, 0.82, 0.165, 1) 0.5s;
		font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
			Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
	.styleize:hover {
		box-shadow: 1px 1px rgba(0, 0, 0, 0.4);
	}
</style>
