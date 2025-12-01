<script>
	import { base } from '$app/paths';
</script>

<div class="grid grid-cols-2">
	<div class="flex flex-col gap-10 p-10">
		<img src={`${base}/images/poesie.jpeg`} alt="Scan" />
	</div>
	<div class="p-15">
		<h1 class="h1">Poesie</h1>
		<p>
			Ogni male che mi fai<br break="no" />
			lo <delete>veli</delete> <add place="above">fai precedere</add> d’<insert>a</insert>una nuova
			tenerezza<br break="no" />
			e non sai<br break="no" />
			che per questo diventa più amaro.<br break="no" />
			<br break="no" />
			<span class="text-right">Losanna, luglio 1943</span><br break="no" />

			<br break="no" />
			<br break="no" />

			Ti ho amata<br break="no" />
			te ne ricordi?<br break="no" />
			Or sulla strada
			<subst
				><delete>bianca</delete>
				<add place="above">
					<subst>
						<delete> e polvere </delete>
						<add place="above">lunga</add>
					</subst>
				</add>
			</subst>
			<br break="no" />

			canta
			<subst>
				<delete>il mio dolore</delete><add place="below"
					>un pianto <delete>solo</delete> lontano</add
				></subst
			>
			<br break="no" />

			<altVariant data-label="Variante alternativa">
				<comment
					>Nel marg. sin. l'autrice annotata una variante alternativa per il quarto verso della
					lirica. Il verso contiene a sua volta un ulteriore serie di varianti alternative per il
					verbo «svanisce» («muore»; «si perde») e l'aggettivo «lontano» («più solo»), appuntate tra
					parentesi tonde.</comment
				>
				<orig>
				<ref>svanisce</ref> <insert place="below">(si perde)</insert>
				<insert place="above">(muore)</insert>
				</orig><reg>svanisce</reg>
				un passo
				<orig>
					<ref>lontano</ref> <insert place="below">(più solo)</insert>
				</orig><reg>lontano</reg>
			</altVariant>
			<br break="no" />
			<altVariant data-label="Variante alternativa">
				<comment
					>Nel marg. sin. l'autrice annotata una variante alternativa per il quarto verso della
					lirica. Il verso contiene a sua volta un ulteriore serie di varianti alternative per il
					verbo «svanisce» («muore»; «si perde») e l'aggettivo «lontano» («più solo»), appuntate tra
					parentesi tonde.</comment
				>
				<orig>
					<ref>svanisce</ref> <insert place="below">(si perde)</insert>
					<insert place="above">(muore)</insert>
				</orig><reg>svanisce</reg>
			</altVariant>
			un passo
			<altVariant data-label="Variante alternativa">
				<comment
					>Nel marg. sin. l'autrice annotata una variante alternativa per il quarto verso della
					lirica. Il verso contiene a sua volta un ulteriore serie di varianti alternative per il
					verbo «svanisce» («muore»; «si perde») e l'aggettivo «lontano» («più solo»), appuntate tra
					parentesi tonde.</comment
				>
				<orig>
					<ref>lontano</ref> <insert place="below">(più solo)</insert>
				</orig><reg>lontano</reg>
			</altVariant>
			<br break="no" />
			dalla finestra nera<br break="no" />
			<delete>odo</delete> <insert place="below">vedo</insert> <delete>tra</delete>scorrere il fiume<br
				break="no"
			/>

			Zurigo, primavera 44.
			<subst>
				<delete>
					<unclear>15</unclear>
				</delete><add place="over">23</add>
			</subst>.4.44.
		</p>
	</div>
</div>
