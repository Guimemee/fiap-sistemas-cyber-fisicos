
			<html>
				<script>
					function fDownload(){
						document.frmDownload.submit();
					}
				</script>
				<body onload="javascript: fDownload();">
					<form name="frmDownload"  method="get" action="/Controle404/download.php">
						<input type="hidden" name="file" value="upload_fiap/alunos/apostilas/Formalizacao_Projeto_Exoesqueleto.md">
						<!--<input type="hidden" name="origem" value="asp">-->
					</form>
				</body>
			</html>
		