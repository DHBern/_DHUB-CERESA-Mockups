{#snippet thead()}
	<thead>
		<tr class="">
			<th
				><div class="flex h-10 w-10 items-center rounded-full bg-blue-200">
					<p class="w-full text-center">DF</p>
				</div></th
			>
			<th
				><div class="flex h-10 w-10 items-center rounded-full bg-red-200">
					<p class="w-full text-center">LF</p>
				</div></th
			>
			<th>Description</th>
		</tr>
	</thead>
{/snippet}
<div class="mx-auto p-20">
	<h1 class="mb-20! h1">Transcription guide</h1>
	<table class="mx-auto mt-10 w-full text-left">
		{@render thead()}
		<tbody>
			<!-- FORMATTING -->
			<tr><th><h3 class="mt-2 h5">Basic Formatting</h3></th></tr>
			<!-- Aligning -->
			<tr>
				<th data-fassung="DF"><p><pagenum type="hand">99</pagenum></p></th>
				<th data-fassung="LF"><p><pagenum type="hand">99</pagenum></p></th>
				<th>Page Numbers</th></tr
			>
			<tr>
				<th data-fassung="DF"><p ana="end-aligned">Alice Ceresa</p></th>
				<th data-fassung="LF"><p ana="end-aligned">Alice Ceresa</p></th>
				<th>Right alignment</th></tr
			>

			<!-- INSERTIONS -->
			<tr><th><h3 class="mt-2 h5">Insertions by Ceresa</h3></th></tr>
			<!-- Hand -->
			<tr>
				<th data-fassung="DF">Alice <add>Ceresa</add></th>
				<th data-fassung="LF">Alice <add>Ceresa</add></th>
				<th>Manuscript text in a typoscript</th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<insert type="hand" place="above">c</insert>e Ceresa</th>
				<th data-fassung="LF">Ali<insert type="hand" place="above">c</insert>e Ceresa</th>
				<th>Insertion above the line by hand</th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<insert type="hand" place="below">c</insert>e Ceresa</th>
				<th data-fassung="LF">Ali<insert type="hand" place="below">c</insert>e Ceresa</th>
				<th>Insertion below the line by hand</th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<insert type="hand" place="inline">c</insert>e Ceresa</th>
				<th data-fassung="LF">Ali<insert type="hand" place="inline">c</insert>e Ceresa</th>
				<th>Insertion within the line by hand</th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<insMargin type="hand">c</insMargin>e Ceresa</th>
				<th data-fassung="LF">Ali<insMargin type="hand">c</insMargin>e Ceresa</th>
				<th
					>Insertion in the margin by hand<br /><strong
						><em>Note: We may actually not need this!</em></strong
					></th
				></tr
			>
			<!-- Typewriter -->
			<tr>
				<th data-fassung="DF">Ali<insert type="typewriter" place="above">c</insert>e Ceresa</th>
				<th data-fassung="LF">Ali<insert type="typewriter" place="above">c</insert>e Ceresa</th>
				<th>Insertion above the line with the typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<insert type="typewriter" place="below">c</insert>e Ceresa</th>
				<th data-fassung="LF">Ali<insert type="typewriter" place="below">c</insert>e Ceresa</th>
				<th>Insertion below the line with the typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<insert type="typewriter" place="inline">c</insert>e Ceresa</th>
				<th data-fassung="LF">Ali<insert type="typewriter" place="inline">c</insert>e Ceresa</th>
				<th>Insertion within the line with the typewriter</th></tr
			>

			<tr>
				<th data-fassung="DF">Ali<insMargin>c</insMargin>e Ceresa</th>
				<th data-fassung="LF">Ali<insMargin>c</insMargin>e Ceresa</th>
				<th
					>Insertion in the margin with the typewriter<br /><strong
						><em>Note: We may actually not need this!</em></strong
					></th
				></tr
			>

			<!-- DELETIONS -->
			<tr><th><h3 class="mt-2 h5">Deletions by Ceresa</h3></th></tr>
			<tr>
				<th data-fassung="DF">Alice <delete type="hand">Ceresa</delete></th>
				<th data-fassung="LF">Alice <delete type="hand">Ceresa</delete></th>
				<th>Crossed out by hand</th></tr
			>
			<tr>
				<th data-fassung="DF">Alice <delete type="typewriter">Ceresa</delete></th>
				<th data-fassung="LF">Alice <delete type="typewriter">Ceresa</delete></th>
				<th>Crossed out with the typewriter</th></tr
			>

			<!-- SUBSTITUTIONS -->
			<tr><th><h3 class="mt-2 h5">Substitutions by Ceresa</h3></th></tr>
			<!-- hand -->
			<tr>
				<th data-fassung="DF"
					><subst type="hand"><delete>Alice</delete> <add place="over">Ceresa</add></subst></th
				>
				<th data-fassung="LF"
					><subst type="hand"><delete>Alice</delete> <add place="over">Ceresa</add></subst></th
				>
				<th>«Ceresa» written over «Alice» by hand</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><subst type="hand"><delete>Alice</delete> <add place="above">Ceresa</add></subst></th
				>
				<th data-fassung="LF"
					><subst type="hand"><delete>Alice</delete> <add place="above">Ceresa</add></subst></th
				>
				<th>«Ceresa» replaces «Alice» above the line by hand</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><subst type="hand"><delete>Alice</delete> <add place="below">Ceresa</add></subst></th
				>
				<th data-fassung="LF"
					><subst type="hand"><delete>Alice</delete> <add place="below">Ceresa</add></subst></th
				>
				<th>«Ceresa» replaces «Alice» below the line by hand</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><subst type="hand"><delete>Alice</delete> <add place="inline">Ceresa</add></subst></th
				>
				<th data-fassung="LF"
					><subst type="hand"><delete>Alice</delete> <add place="inline">Ceresa</add></subst></th
				>
				<th>«Ceresa» replaces «Alice» within the line by hand</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><substMargin type="hand"><delete>Alice</delete> <add>Ceresa</add></substMargin></th
				>
				<th data-fassung="LF"
					><substMargin type="hand"><delete>Alice</delete> <add>Ceresa</add></substMargin></th
				>
				<th
					>«Ceresa» replaces «Alice» in the margin by hand<br /><strong
						><em>Note: We may actually not need this!</em></strong
					></th
				></tr
			>
			<!-- Typewriter -->
			<tr>
				<th data-fassung="DF"
					><subst type="typewriter"><delete>Alice</delete> <add place="over">Ceresa</add></subst
					></th
				>
				<th data-fassung="LF"
					><subst type="typewriter"><delete>Alice</delete> <add place="over">Ceresa</add></subst
					></th
				>
				<th>«Ceresa» written over «Alice» with the typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><subst type="typewriter"><delete>Alice</delete> <add place="above">Ceresa</add></subst
					></th
				>
				<th data-fassung="LF"
					><subst type="typewriter"><delete>Alice</delete> <add place="above">Ceresa</add></subst
					></th
				>
				<th>«Ceresa» replaces «Alice» above the line with the typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><subst type="typewriter"><delete>Alice</delete> <add place="below">Ceresa</add></subst
					></th
				>
				<th data-fassung="LF"
					><subst type="typewriter"><delete>Alice</delete> <add place="below">Ceresa</add></subst
					></th
				>
				<th>«Ceresa» replaces «Alice» below the line with the typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><subst type="typewriter"><delete>Alice</delete> <add place="inline">Ceresa</add></subst
					></th
				>
				<th data-fassung="LF"
					><subst type="typewriter"><delete>Alice</delete> <add place="inline">Ceresa</add></subst
					></th
				>
				<th>«Ceresa» replaces «Alice» within the line with the typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF"
					><substMargin type="typewriter"><delete>Alice</delete> <add>Ceresa</add></substMargin></th
				>
				<th data-fassung="LF"
					><substMargin type="typewriter"><delete>Alice</delete> <add>Ceresa</add></substMargin></th
				>
				<th
					>«Ceresa» replaces «Alice» in the margin with the typewriter<br /><strong
						><em>Note: We may actually not need them!</em></strong
					></th
				></tr
			>
			<!-- Mixed -->
			<tr>
				<th data-fassung="DF"
					><subst
						><delete type="typewriter">Alice</delete>
						<add type="hand" place="above">Ceresa</add></subst
					></th
				>
				<th data-fassung="LF"
					><subst
						><delete type="typewriter">Alice</delete>
						<add type="hand" place="above">Ceresa</add></subst
					></th
				>
				<th
					>Mixed case: «Ceresa» (handwritten) replaces «Alice» above the line, where the latter is
					striked through. <span class="text-red-500">Is this ever needed?</span></th
				></tr
			>

			<!-- Repositioning -->
			<tr><th><h3 class="mt-2 h5">Repositioning by Ceresa</h3></th></tr>

			<tr>
				<th data-fassung="DF"
					><movedBlockRef data-ref="1" />Alice
					<movedBlock data-ref="1" data-label="Paragrafo riposizionato">Ceresa</movedBlock></th
				>
				<th data-fassung="LF"
					><movedBlockRef data-ref="1" />Alice
					<movedBlock data-ref="1" data-label="Paragrafo riposizionato">Ceresa</movedBlock></th
				>
				<th>Repositioned paragraph<br /><strong><em>Hover it with your mouse!</em></strong></th>
			</tr>

			<tr>
				<th data-fassung="DF"
					><movedBlockRef data-ref="2" />Alice
					<movedBlock data-ref="2" data-label="Parola riposizionato">Ceresa</movedBlock></th
				>
				<th data-fassung="LF"
					><movedBlockRef data-ref="2" />Alice
					<movedBlock data-ref="2" data-label="Parola riposizionato">Ceresa</movedBlock></th
				>
				<th>Repositioned word<br /><strong><em>Hover it with your mouse!</em></strong></th>
			</tr>

			<tr><th><h3 class="mt-2 h5">Variants</h3></th></tr>

			<tr
				><th data-fassung="DF">
					<altVariant data-label="Variante alternativa">
						<comment>A short comment<br /></comment>
						<orig>
							<ref>Alice Ceresa</ref>
							<insert place="above">Alice</insert>
							<insert place="below">Ceresa</insert>
						</orig>
						<reg>Alice</reg>
					</altVariant>
				</th><th data-fassung="LF">
					<altVariant data-label="Variante alternativa"
						><orig>
							<ref>Alice Ceresa</ref>
							<insert place="above">Alice</insert>
							<insert place="below">Ceresa</insert>
						</orig>
						<reg>Alice</reg>
					</altVariant>
				</th><th
					>Alternative ways of writing «Alice Ceresa» are «Alice» and «Ceresa». «Alice» was chosen
					to be displayed in LF.<br />
					The green highlight is not needed here, but if multiple alternatives should be contained in
					one box, then some marker is required.
				</th>
			</tr>

			<!-- Page annotation by Ceresa -->
			<tr><th><h3 class="mt-2 h5">Page annotations by Ceresa</h3></th></tr>
			<tr>
				<th data-fassung="DF"><pagenum type="hand">11</pagenum></th>
				<th data-fassung="LF"><pagenum type="hand">11</pagenum></th>
				<th>Page Number by hand on a typewriter-page</th></tr
			>
			<tr>
				<th data-fassung="DF"><pagenum type="typewriter">11</pagenum></th>
				<th data-fassung="LF"><pagenum type="typewriter">11</pagenum></th>
				<th>Page Number with typewriter</th></tr
			>
			<tr>
				<th data-fassung="DF"><pagenum>11</pagenum></th>
				<th data-fassung="LF"><pagenum>11</pagenum></th>
				<th>Page Number by hand on a handwritten page</th></tr
			>

			<!-- Editorial Interventions -->
			<tr><th><h3 class="mt-2 h5">Editorial Interventions</h3></th></tr>
			<tr>
				<th data-fassung="DF">Alice Ceres<insEditorial>a</insEditorial></th>
				<th data-fassung="LF">Alice Ceres<insEditorial>a</insEditorial></th>
				<th>Editorial insertion</th></tr
			>
			<tr>
				<th data-fassung="DF"
					>Alice Ceres<choice><orig>A</orig><reg><add>a</add></reg></choice>
				</th>
				<th data-fassung="LF"
					>Alice Ceres<choice><orig>A</orig><reg><add>a</add></reg> </choice>
				</th>
				<th>Editorial choice <strong><em>(part of word)</em></strong></th></tr
			>
			<tr>
				<th data-fassung="DF"
					>Alice <choice>
						<orig>ceresA</orig>
						<reg><add>Ceresa</add></reg>
					</choice>
				</th>
				<th data-fassung="LF"
					>Alice <choice>
						<orig>ceresA</orig>
						<reg><add>Ceresa</add></reg>
					</choice>
				</th>
				<th>Editorial choice <strong><em>(full word or longer)</em></strong></th></tr
			>
			<tr>
				<th data-fassung="DF">Ali<unclear>ce Ceresa</unclear></th>
				<th data-fassung="LF">Ali<unclear>ce Ceresa</unclear></th>
				<th
					>Uncertain reading. The parantheses show, what part is uncertain. <br />
					<strong
						><em
							>Note: This can be just a few letters or multiple words!<br />
							Also: In LF it won't be clear what the [?] refers to.<br />
							Also: If only the first part of a word is unclear, shall [?] go inside the word?
						</em></strong
					></th
				></tr
			>
			<tr>
				<th data-fassung="DF">Alice <illegible>xxx</illegible> Ceresa</th>
				<th data-fassung="LF">Alice <illegible>xxx</illegible> Ceresa</th>
				<th>Illegible word (1 x = approx. 1 letter)</th></tr
			>
		</tbody>
	</table>

	<h1 class="mt-30 mb-20! h1">Semantic Annotations</h1>
	<table class="mx-auto mt-10 w-full text-left">
		<thead></thead>
		<tbody>
			<tr
				><th class="font-bold! italic"
					>Different combinations to get a feel about what's possible. Of course we should choose
					one of these options.</th
				></tr
			>
			<tr>
				<th data-fassung="DF">This is how <a type="place" href="">Places</a> are highlighted.</th
				></tr
			>
			<tr
				><th data-fassung="DF">This is how <a type="person" href="">People</a> are highlighted.</th
				></tr
			>
			<tr
				><th data-fassung="DF"
					>This is how <a type="org" href="">Publishing houses</a> and other
					<a type="org" href="">Organisations</a> are highlighted.</th
				></tr
			>
			<tr
				><th data-fassung="DF">This is how <a type="work" href="">Works</a> are highlighted.</th
				></tr
			>
			<tr
				><th data-fassung="DF"
					>This is how <a type="citation" href="">Citations</a> are highlighted.</th
				></tr
			>
			<tr
				><th data-fassung="DF">This is how <a type="topic" href="">Topics</a> are highlighted.</th
				></tr
			>
		</tbody>
	</table>
</div>

<style>
	@reference "tailwindcss";
	thead th {
		@apply px-4 py-2 font-bold;
	}
	tbody th {
		@apply px-4 py-2 font-normal;
	}
</style>
