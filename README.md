<!DOCTYPE html>
  <html lang="fr">
	<head>
		<meta charset="UTF-8">
		<title>inscriptionBac</title>
    </head>
	<body>  
	<p1>sfendji lina malak</p1>
	  <h1>INSCRIPTION:</h1>
		<form methode="GET" action="http://127.PHP">
			<fieldset>
				<legend>Candidat</legend>
					<fieldset>
						<legend>Identete</legend>
							<label>sexe :</label>
								<select name="sexe" >
									<option value="homme" selected>Homme</option>
			                        <option value="femme">Femme</option>
								</select>
							<label>situation :</label>
								<select name="situation">
									<option value="marie" selected>Marie</option>
									<option value="devorce">Devorce</option>
									<option value="celebataire">Celebataire</option>
									<option value="veuf">Veuf</option>
								</select><br><br>
							<label>Nom/Prenom :</label>
							<input type="texte" name="nom_prenom"><br>
							<label>Adresse:</label><br>
							<textarea name="adress" placeholder="Rue No 
							Boite postale" rows="3" cols="40"></textarea><br>
							<label>Code postale/Ville</label>
							<input type="texte" name="codepostale_ville"><input type="texte" value="Alger"><label>Wilaya:</label>
							<select name="wilaya">
								<option value="adrar" selected>01 Adrar</option>
								<option value="alger">16 Alger</option>
								<option value="bouira">10 Bouira</option>
								<option value="blida">09 Blida</option>
								<option value="tizi ouzou">15 Tizi ouzou</option>
								<option value="batna">05 Batna</option>
							</select>
					</fieldset>
					<fieldset>
						<legend align="center">Connaissances en Informatique</legend>
						<label>Plateforme(s):</label>
						<input type="checkbox" name="windows" checked>
						<label>Windows</label>
						<input type="checkbox" name="macintosh">
						<label>Maccintosh</label>
						<input type="checkbox" name="unix" checked>
						<label>Unix</label><br>
						<label>Application(s):</label>
						<select name="Application">
							<option value="bureautique">Bureutique</option>
							<option value="houda">Houda</option>
							<option value="nour">Nour</option>
						</select>
					</fieldset><br>
					<label>Envoyez votre CV detaille :</label>
					<input type="file" accept=".PDF,.DOX">
			</fieldset>
			<input type="submit" value="valider">
			<input type="reset" value="Effacer">
		</form>
	</body>
  </html>
