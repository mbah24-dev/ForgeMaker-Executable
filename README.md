<!DOCTYPE html>
<html lang="fr">
<body>
    <h1>ForgeMaker</h1>
    <p><strong>ForgeMaker</strong> est un outil conçu pour générer automatiquement un Makefile en scannant les répertoires du dossier courant. Il nécessite au minimum la présence de deux répertoires :</p>
    <ul>
        <li><strong>src</strong> : contenant les fichiers source</li>
        <li><strong>inc</strong> : contenant les fichiers d’en-tête</li>
    </ul>
    <p>Si ces répertoires ne sont pas présents, <strong>ForgeMaker</strong> ne pourra pas générer le Makefile et affichera un message d’erreur.</p>
    <h2>Comment Utiliser</h2>
    <ol>
        <li>Téléchargez l’exécutable depuis ce dépôt.</li>
        <li>Donnez-lui les droits d'exécution :</li>
        <pre><code>chmod +x ForgeMaker</code></pre>
        <li>Si vous êtes sur macOS, autorisez son exécution :</li>
        <ol>
            <li>Accédez à <strong>Paramètres</strong> > <strong>Confidentialité et sécurité</strong>.</li>
            <li>En bas de la section, cliquez sur <strong>Autoriser ForgeMaker</strong>.</li>
        </ol>
        <li>Assurez-vous que votre répertoire de travail contient les dossiers <code>src</code> et <code>inc</code>.</li>
        <li>Exécutez ForgeMaker :</li>
        <pre><code>./ForgeMaker <Répertoire_fichiers_header> <Répertoire_fichiers_source></code></pre>
        <li>Le Makefile sera généré dans le répertoire courant.</li>
    </ol>
    <h2>Téléchargement</h2>
    <p>Vous pouvez télécharger l’exécutable précompilé dans la section <a href="releases">Releases</a> de ce dépôt.</p>
    <h2>Licence</h2>
    <p>Ce projet est sous licence <strong>MIT</strong>. Consultez le fichier LICENSE pour plus de détails.</p>
</body>
</html>
