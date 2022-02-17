# AncientLife.github.io
Were Mass Extinctions Fast or Slow?
By Anna, Clementine, Rachel and Elise
@import url(fontawesome-all.min.css);
@import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,300i,400,400i");

/*
	Story by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
*/

html, body, div, span, applet, object,
iframe, h1, h2, h3, h4, h5, h6, p, blockquote,
pre, a, abbr, acronym, address, big, cite,
code, del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var, b,
u, i, center, dl, dt, dd, ol, ul, li, fieldset,
form, label, legend, table, caption, tbody,
tfoot, thead, tr, th, td, article, aside,
canvas, details, embed, figure, figcaption,
footer, header, hgroup, menu, nav, output, ruby,
section, summary, time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;}

article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;}

body {
	line-height: 1;
}

ol, ul {
	list-style: none;
}

blockquote, q {
	quotes: none;
}

	blockquote:before, blockquote:after, q:before, q:after {
		content: '';
		content: none;
	}

table {
	border-collapse: collapse;
	border-spacing: 0;
}

body {
	-webkit-text-size-adjust: none;
}

mark {
	background-color: transparent;
	color: inherit;
}

input::-moz-focus-inner {
	border: 0;
	padding: 0;
}

input, select, textarea {
	-moz-appearance: none;
	-webkit-appearance: none;
	-ms-appearance: none;
	appearance: none;
}

/* Basic */

	@-ms-viewport {
		width: device-width;
	}

	body {
		-ms-overflow-style: scrollbar;
	}

	@media screen and (max-width: 480px) {

		html, body {
			min-width: 320px;
		}

	}

	html {
		box-sizing: border-box;
	}

	*, *:before, *:after {
		box-sizing: inherit;
	}

	body {
		background: #ffffff;
	}

		body.is-preload *, body.is-preload *:before, body.is-preload *:after {
			-moz-animation: none !important;
			-webkit-animation: none !important;
			-ms-animation: none !important;
			animation: none !important;
			-moz-transition: none !important;
			-webkit-transition: none !important;
			-ms-transition: none !important;
			transition: none !important;
		}

/* Type */

	html {
		font-size: 18pt;
	}

		@media screen and (max-width: 1680px) {

			html {
				font-size: 14pt;
			}

		}

		@media screen and (max-width: 1280px) {

			html {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 736px) {

			html {
				font-size: 11pt;
			}

		}

		@media screen and (max-width: 360px) {

			html {
				font-size: 10pt;
			}

		}

	body {
		background-color: #ffffff;
		color: #000000;
	}

	body, input, select, textarea {
		font-family: "Source Sans Pro", Helvetica, sans-serif;
		font-size: 1rem;
		font-weight: 300;
		line-height: 1.65;
	}

	a {
		-moz-transition: color 0.2s ease-in-out;
		-webkit-transition: color 0.2s ease-in-out;
		-ms-transition: color 0.2s ease-in-out;
		transition: color 0.2s ease-in-out;
		text-decoration: underline;
	}

		a:hover {
			text-decoration: none;
		}

	strong, b {
		font-weight: 400;
	}

	em, i {
		font-style: italic;
	}

	p {
		margin: 0 0 2rem 0;
	}

		p.major {
			font-size: 1.25rem;
		}

	h1, h2, h3, h4, h5, h6 {
		font-weight: 300;
		line-height: 1.375;
		letter-spacing: -0.05em;
		margin: 0 0 1rem 0;
	}

		h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
			color: inherit;
			text-decoration: none;
		}

	h1 {
		font-size: 3.5rem;
		line-height: 1.2;
	}

	h2 {
		font-size: 2.25rem;
	}

	h3 {
		font-size: 1.5rem;
	}

	h4 {
		font-size: 1.1rem;
	}

	h5 {
		font-size: 0.9rem;
	}

	h6 {
		font-size: 0.7rem;
	}

	sub {
		font-size: 0.8rem;
		position: relative;
		top: 0.5rem;
	}

	sup {
		font-size: 0.8rem;
		position: relative;
		top: -0.5rem;
	}

	blockquote {
		border-left: solid 4px;
		font-style: italic;
		margin: 0 0 2rem 0;
		padding: 0.5rem 0 0.5rem 2rem;
	}

	code {
		border-radius: 4px;
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0.25rem;
		padding: 0.25rem 0.325rem;
	}

	pre {
		-webkit-overflow-scrolling: touch;
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0 2rem 0;
	}

		pre code {
			display: block;
			line-height: 1.5;
			padding: 0.75rem 1rem;
			overflow-x: auto;
		}

	hr {
		border: 0;
		border-bottom: solid 1px;
		margin: 2.5rem 0;
	}

		hr.major {
			margin: 3.5rem 0;
		}

	.align-left {
		text-align: left;
	}

	.align-center {
		text-align: center;
	}

	.align-right {
		text-align: right;
	}

	@media screen and (max-width: 736px) {

		p.major {
			font-size: 1.1rem;
		}

		h1 {
			font-size: 2.5rem;
		}

		h2 {
			font-size: 2rem;
		}

		h3 {
			font-size: 1.25rem;
		}

		h4 {
			font-size: 1rem;
		}

	}

	input, select, textarea {
		color: #000000;
	}

	a {
		color: #000000;
	}

		a:hover {
			color: #47D3E5;
		}

	strong, b {
		color: #000000;
	}

	h1, h2, h3, h4, h5, h6 {
		color: #000000;
	}

	blockquote {
		border-left-color: rgba(0, 0, 0, 0.2);
	}

	code {
		background: rgba(0, 0, 0, 0.05);
		border-color: rgba(0, 0, 0, 0.2);
	}

	hr {
		border-bottom-color: rgba(0, 0, 0, 0.2);
	}

/* Row */

	.row {
		display: flex;
		flex-wrap: wrap;
		box-sizing: border-box;
		align-items: stretch;
	}

		.row > * {
			box-sizing: border-box;
		}

		.row.gtr-uniform > * > :last-child {
			margin-bottom: 0;
		}

		.row.aln-left {
			justify-content: flex-start;
		}

		.row.aln-center {
			justify-content: center;
		}

		.row.aln-right {
			justify-content: flex-end;
		}

		.row.aln-top {
			align-items: flex-start;
		}

		.row.aln-middle {
			align-items: center;
		}

		.row.aln-bottom {
			align-items: flex-end;
		}

		.row > .imp {
			order: -1;
		}

		.row > .col-1 {
			width: 8.33333%;
		}

		.row > .off-1 {
			margin-left: 8.33333%;
		}

		.row > .col-2 {
			width: 16.66667%;
		}

		.row > .off-2 {
			margin-left: 16.66667%;
		}

		.row > .col-3 {
			width: 25%;
		}

		.row > .off-3 {
			margin-left: 25%;
		}

		.row > .col-4 {
			width: 33.33333%;
		}

		.row > .off-4 {
			margin-left: 33.33333%;
		}

		.row > .col-5 {
			width: 41.66667%;
		}

		.row > .off-5 {
			margin-left: 41.66667%;
		}

		.row > .col-6 {
			width: 50%;
		}

		.row > .off-6 {
			margin-left: 50%;
		}

		.row > .col-7 {
			width: 58.33333%;
		}

		.row > .off-7 {
			margin-left: 58.33333%;
		}

		.row > .col-8 {
			width: 66.66667%;
		}

		.row > .off-8 {
			margin-left: 66.66667%;
		}

		.row > .col-9 {
			width: 75%;
		}

		.row > .off-9 {
			margin-left: 75%;
		}

		.row > .col-10 {
			width: 83.33333%;
		}

		.row > .off-10 {
			margin-left: 83.33333%;
		}

		.row > .col-11 {
			width: 91.66667%;
		}

		.row > .off-11 {
			margin-left: 91.66667%;
		}

		.row > .col-12 {
			width: 100%;
		}

		.row > .off-12 {
			margin-left: 100%;
		}

		.row.gtr-0 {
			margin-top: 0;
			margin-left: 0rem;
		}

			.row.gtr-0 > * {
				padding: 0 0 0 0rem;
			}

			.row.gtr-0.gtr-uniform {
				margin-top: 0rem;
			}

				.row.gtr-0.gtr-uniform > * {
					padding-top: 0rem;
				}

		.row.gtr-25 {
			margin-top: 0;
			margin-left: -0.5rem;
		}

			.row.gtr-25 > * {
				padding: 0 0 0 0.5rem;
			}

			.row.gtr-25.gtr-uniform {
				margin-top: -0.5rem;
			}

				.row.gtr-25.gtr-uniform > * {
					padding-top: 0.5rem;
				}

		.row.gtr-50 {
			margin-top: 0;
			margin-left: -1rem;
		}

			.row.gtr-50 > * {
				padding: 0 0 0 1rem;
			}

			.row.gtr-50.gtr-uniform {
				margin-top: -1rem;
			}

				.row.gtr-50.gtr-uniform > * {
					padding-top: 1rem;
				}

		.row {
			margin-top: 0;
			margin-left: -2rem;
		}

			.row > * {
				padding: 0 0 0 2rem;
			}

			.row.gtr-uniform {
				margin-top: -2rem;
			}

				.row.gtr-uniform > * {
					padding-top: 2rem;
				}

		.row.gtr-150 {
			margin-top: 0;
			margin-left: -3rem;
		}

			.row.gtr-150 > * {
				padding: 0 0 0 3rem;
			}

			.row.gtr-150.gtr-uniform {
				margin-top: -3rem;
			}

				.row.gtr-150.gtr-uniform > * {
					padding-top: 3rem;
				}

		.row.gtr-200 {
			margin-top: 0;
			margin-left: -4rem;
		}

			.row.gtr-200 > * {
				padding: 0 0 0 4rem;
			}

			.row.gtr-200.gtr-uniform {
				margin-top: -4rem;
			}

				.row.gtr-200.gtr-uniform > * {
					padding-top: 4rem;
				}

		@media screen and (max-width: 1680px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xlarge {
					order: -1;
				}

				.row > .col-1-xlarge {
					width: 8.33333%;
				}

				.row > .off-1-xlarge {
					margin-left: 8.33333%;
				}

				.row > .col-2-xlarge {
					width: 16.66667%;
				}

				.row > .off-2-xlarge {
					margin-left: 16.66667%;
				}

				.row > .col-3-xlarge {
					width: 25%;
				}

				.row > .off-3-xlarge {
					margin-left: 25%;
				}

				.row > .col-4-xlarge {
					width: 33.33333%;
				}

				.row > .off-4-xlarge {
					margin-left: 33.33333%;
				}

				.row > .col-5-xlarge {
					width: 41.66667%;
				}

				.row > .off-5-xlarge {
					margin-left: 41.66667%;
				}

				.row > .col-6-xlarge {
					width: 50%;
				}

				.row > .off-6-xlarge {
					margin-left: 50%;
				}

				.row > .col-7-xlarge {
					width: 58.33333%;
				}

				.row > .off-7-xlarge {
					margin-left: 58.33333%;
				}

				.row > .col-8-xlarge {
					width: 66.66667%;
				}

				.row > .off-8-xlarge {
					margin-left: 66.66667%;
				}

				.row > .col-9-xlarge {
					width: 75%;
				}

				.row > .off-9-xlarge {
					margin-left: 75%;
				}

				.row > .col-10-xlarge {
					width: 83.33333%;
				}

				.row > .off-10-xlarge {
					margin-left: 83.33333%;
				}

				.row > .col-11-xlarge {
					width: 91.66667%;
				}

				.row > .off-11-xlarge {
					margin-left: 91.66667%;
				}

				.row > .col-12-xlarge {
					width: 100%;
				}

				.row > .off-12-xlarge {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0rem;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0rem;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0rem;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0rem;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.5rem;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.5rem;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.5rem;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.5rem;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -1rem;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 1rem;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -1rem;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 1rem;
						}

				.row {
					margin-top: 0;
					margin-left: -2rem;
				}

					.row > * {
						padding: 0 0 0 2rem;
					}

					.row.gtr-uniform {
						margin-top: -2rem;
					}

						.row.gtr-uniform > * {
							padding-top: 2rem;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -3rem;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 3rem;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -3rem;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 3rem;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -4rem;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 4rem;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -4rem;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 4rem;
						}

		}

		@media screen and (max-width: 1280px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-large {
					order: -1;
				}

				.row > .col-1-large {
					width: 8.33333%;
				}

				.row > .off-1-large {
					margin-left: 8.33333%;
				}

				.row > .col-2-large {
					width: 16.66667%;
				}

				.row > .off-2-large {
					margin-left: 16.66667%;
				}

				.row > .col-3-large {
					width: 25%;
				}

				.row > .off-3-large {
					margin-left: 25%;
				}

				.row > .col-4-large {
					width: 33.33333%;
				}

				.row > .off-4-large {
					margin-left: 33.33333%;
				}

				.row > .col-5-large {
					width: 41.66667%;
				}

				.row > .off-5-large {
					margin-left: 41.66667%;
				}

				.row > .col-6-large {
					width: 50%;
				}

				.row > .off-6-large {
					margin-left: 50%;
				}

				.row > .col-7-large {
					width: 58.33333%;
				}

				.row > .off-7-large {
					margin-left: 58.33333%;
				}

				.row > .col-8-large {
					width: 66.66667%;
				}

				.row > .off-8-large {
					margin-left: 66.66667%;
				}

				.row > .col-9-large {
					width: 75%;
				}

				.row > .off-9-large {
					margin-left: 75%;
				}

				.row > .col-10-large {
					width: 83.33333%;
				}

				.row > .off-10-large {
					margin-left: 83.33333%;
				}

				.row > .col-11-large {
					width: 91.66667%;
				}

				.row > .off-11-large {
					margin-left: 91.66667%;
				}

				.row > .col-12-large {
					width: 100%;
				}

				.row > .off-12-large {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0rem;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0rem;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0rem;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0rem;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.5rem;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.5rem;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.5rem;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.5rem;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -1rem;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 1rem;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -1rem;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 1rem;
						}

				.row {
					margin-top: 0;
					margin-left: -2rem;
				}

					.row > * {
						padding: 0 0 0 2rem;
					}

					.row.gtr-uniform {
						margin-top: -2rem;
					}

						.row.gtr-uniform > * {
							padding-top: 2rem;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -3rem;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 3rem;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -3rem;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 3rem;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -4rem;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 4rem;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -4rem;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 4rem;
						}

		}

		@media screen and (max-width: 980px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-medium {
					order: -1;
				}

				.row > .col-1-medium {
					width: 8.33333%;
				}

				.row > .off-1-medium {
					margin-left: 8.33333%;
				}

				.row > .col-2-medium {
					width: 16.66667%;
				}

				.row > .off-2-medium {
					margin-left: 16.66667%;
				}

				.row > .col-3-medium {
					width: 25%;
				}

				.row > .off-3-medium {
					margin-left: 25%;
				}

				.row > .col-4-medium {
					width: 33.33333%;
				}

				.row > .off-4-medium {
					margin-left: 33.33333%;
				}

				.row > .col-5-medium {
					width: 41.66667%;
				}

				.row > .off-5-medium {
					margin-left: 41.66667%;
				}

				.row > .col-6-medium {
					width: 50%;
				}

				.row > .off-6-medium {
					margin-left: 50%;
				}

				.row > .col-7-medium {
					width: 58.33333%;
				}

				.row > .off-7-medium {
					margin-left: 58.33333%;
				}

				.row > .col-8-medium {
					width: 66.66667%;
				}

				.row > .off-8-medium {
					margin-left: 66.66667%;
				}

				.row > .col-9-medium {
					width: 75%;
				}

				.row > .off-9-medium {
					margin-left: 75%;
				}

				.row > .col-10-medium {
					width: 83.33333%;
				}

				.row > .off-10-medium {
					margin-left: 83.33333%;
				}

				.row > .col-11-medium {
					width: 91.66667%;
				}

				.row > .off-11-medium {
					margin-left: 91.66667%;
				}

				.row > .col-12-medium {
					width: 100%;
				}

				.row > .off-12-medium {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0rem;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0rem;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0rem;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0rem;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.5rem;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.5rem;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.5rem;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.5rem;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -1rem;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 1rem;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -1rem;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 1rem;
						}

				.row {
					margin-top: 0;
					margin-left: -2rem;
				}

					.row > * {
						padding: 0 0 0 2rem;
					}

					.row.gtr-uniform {
						margin-top: -2rem;
					}

						.row.gtr-uniform > * {
							padding-top: 2rem;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -3rem;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 3rem;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -3rem;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 3rem;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -4rem;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 4rem;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -4rem;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 4rem;
						}

		}

		@media screen and (max-width: 736px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-small {
					order: -1;
				}

				.row > .col-1-small {
					width: 8.33333%;
				}

				.row > .off-1-small {
					margin-left: 8.33333%;
				}

				.row > .col-2-small {
					width: 16.66667%;
				}

				.row > .off-2-small {
					margin-left: 16.66667%;
				}

				.row > .col-3-small {
					width: 25%;
				}

				.row > .off-3-small {
					margin-left: 25%;
				}

				.row > .col-4-small {
					width: 33.33333%;
				}

				.row > .off-4-small {
					margin-left: 33.33333%;
				}

				.row > .col-5-small {
					width: 41.66667%;
				}

				.row > .off-5-small {
					margin-left: 41.66667%;
				}

				.row > .col-6-small {
					width: 50%;
				}

				.row > .off-6-small {
					margin-left: 50%;
				}

				.row > .col-7-small {
					width: 58.33333%;
				}

				.row > .off-7-small {
					margin-left: 58.33333%;
				}

				.row > .col-8-small {
					width: 66.66667%;
				}

				.row > .off-8-small {
					margin-left: 66.66667%;
				}

				.row > .col-9-small {
					width: 75%;
				}

				.row > .off-9-small {
					margin-left: 75%;
				}

				.row > .col-10-small {
					width: 83.33333%;
				}

				.row > .off-10-small {
					margin-left: 83.33333%;
				}

				.row > .col-11-small {
					width: 91.66667%;
				}

				.row > .off-11-small {
					margin-left: 91.66667%;
				}

				.row > .col-12-small {
					width: 100%;
				}

				.row > .off-12-small {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0rem;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0rem;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0rem;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0rem;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.5rem;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.5rem;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.5rem;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.5rem;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -1rem;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 1rem;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -1rem;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 1rem;
						}

				.row {
					margin-top: 0;
					margin-left: -2rem;
				}

					.row > * {
						padding: 0 0 0 2rem;
					}

					.row.gtr-uniform {
						margin-top: -2rem;
					}

						.row.gtr-uniform > * {
							padding-top: 2rem;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -3rem;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 3rem;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -3rem;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 3rem;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -4rem;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 4rem;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -4rem;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 4rem;
						}

		}

		@media screen and (max-width: 480px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xsmall {
					order: -1;
				}

				.row > .col-1-xsmall {
					width: 8.33333%;
				}

				.row > .off-1-xsmall {
					margin-left: 8.33333%;
				}

				.row > .col-2-xsmall {
					width: 16.66667%;
				}

				.row > .off-2-xsmall {
					margin-left: 16.66667%;
				}

				.row > .col-3-xsmall {
					width: 25%;
				}

				.row > .off-3-xsmall {
					margin-left: 25%;
				}

				.row > .col-4-xsmall {
					width: 33.33333%;
				}

				.row > .off-4-xsmall {
					margin-left: 33.33333%;
				}

				.row > .col-5-xsmall {
					width: 41.66667%;
				}

				.row > .off-5-xsmall {
					margin-left: 41.66667%;
				}

				.row > .col-6-xsmall {
					width: 50%;
				}

				.row > .off-6-xsmall {
					margin-left: 50%;
				}

				.row > .col-7-xsmall {
					width: 58.33333%;
				}

				.row > .off-7-xsmall {
					margin-left: 58.33333%;
				}

				.row > .col-8-xsmall {
					width: 66.66667%;
				}

				.row > .off-8-xsmall {
					margin-left: 66.66667%;
				}

				.row > .col-9-xsmall {
					width: 75%;
				}

				.row > .off-9-xsmall {
					margin-left: 75%;
				}

				.row > .col-10-xsmall {
					width: 83.33333%;
				}

				.row > .off-10-xsmall {
					margin-left: 83.33333%;
				}

				.row > .col-11-xsmall {
					width: 91.66667%;
				}

				.row > .off-11-xsmall {
					margin-left: 91.66667%;
				}

				.row > .col-12-xsmall {
					width: 100%;
				}

				.row > .off-12-xsmall {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0rem;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0rem;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0rem;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0rem;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.5rem;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.5rem;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.5rem;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.5rem;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -1rem;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 1rem;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -1rem;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 1rem;
						}

				.row {
					margin-top: 0;
					margin-left: -2rem;
				}

					.row > * {
						padding: 0 0 0 2rem;
					}

					.row.gtr-uniform {
						margin-top: -2rem;
					}

						.row.gtr-uniform > * {
							padding-top: 2rem;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -3rem;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 3rem;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -3rem;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 3rem;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -4rem;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 4rem;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -4rem;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 4rem;
						}

		}

		@media screen and (max-width: 360px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xxsmall {
					order: -1;
				}

				.row > .col-1-xxsmall {
					width: 8.33333%;
				}

				.row > .off-1-xxsmall {
					margin-left: 8.33333%;
				}

				.row > .col-2-xxsmall {
					width: 16.66667%;
				}

				.row > .off-2-xxsmall {
					margin-left: 16.66667%;
				}

				.row > .col-3-xxsmall {
					width: 25%;
				}

				.row > .off-3-xxsmall {
					margin-left: 25%;
				}

				.row > .col-4-xxsmall {
					width: 33.33333%;
				}

				.row > .off-4-xxsmall {
					margin-left: 33.33333%;
				}

				.row > .col-5-xxsmall {
					width: 41.66667%;
				}

				.row > .off-5-xxsmall {
					margin-left: 41.66667%;
				}

				.row > .col-6-xxsmall {
					width: 50%;
				}

				.row > .off-6-xxsmall {
					margin-left: 50%;
				}

				.row > .col-7-xxsmall {
					width: 58.33333%;
				}

				.row > .off-7-xxsmall {
					margin-left: 58.33333%;
				}

				.row > .col-8-xxsmall {
					width: 66.66667%;
				}

				.row > .off-8-xxsmall {
					margin-left: 66.66667%;
				}

				.row > .col-9-xxsmall {
					width: 75%;
				}

				.row > .off-9-xxsmall {
					margin-left: 75%;
				}

				.row > .col-10-xxsmall {
					width: 83.33333%;
				}

				.row > .off-10-xxsmall {
					margin-left: 83.33333%;
				}

				.row > .col-11-xxsmall {
					width: 91.66667%;
				}

				.row > .off-11-xxsmall {
					margin-left: 91.66667%;
				}

				.row > .col-12-xxsmall {
					width: 100%;
				}

				.row > .off-12-xxsmall {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0rem;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0rem;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0rem;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0rem;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.5rem;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.5rem;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.5rem;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.5rem;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -1rem;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 1rem;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -1rem;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 1rem;
						}

				.row {
					margin-top: 0;
					margin-left: -2rem;
				}

					.row > * {
						padding: 0 0 0 2rem;
					}

					.row.gtr-uniform {
						margin-top: -2rem;
					}

						.row.gtr-uniform > * {
							padding-top: 2rem;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -3rem;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 3rem;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -3rem;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 3rem;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -4rem;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 4rem;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -4rem;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 4rem;
						}

		}

/* Box */

	.box {
		border-radius: 4px;
		border: solid 1px;
		margin-bottom: 2rem;
		padding: 1.5rem;
	}

		.box > :last-child,
		.box > :last-child > :last-child,
		.box > :last-child > :last-child > :last-child {
			margin-bottom: 0;
		}

		.box.alt {
			border: 0;
			border-radius: 0;
			padding: 0;
		}

	.box {
		border-color: rgba(0, 0, 0, 0.2);
	}

/* Button */

	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	.button {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		border: 0;
		cursor: pointer;
		display: inline-block;
		font-weight: 400;
		letter-spacing: 0.125em;
		text-align: center;
		text-decoration: none;
		text-transform: uppercase;
		white-space: nowrap;
		font-size: 0.75rem;
		max-width: 20rem;
		height: 3.75em;
		line-height: 3.75em;
		border-radius: 3.75em;
		padding: 0 2.5em;
		text-overflow: ellipsis;
		overflow: hidden;
	}

		input[type="submit"].icon:before,
		input[type="reset"].icon:before,
		input[type="button"].icon:before,
		button.icon:before,
		.button.icon:before {
			margin-right: 0.5rem;
		}

		input[type="submit"].fit,
		input[type="reset"].fit,
		input[type="button"].fit,
		button.fit,
		.button.fit {
			width: 100%;
		}

		input[type="submit"].small,
		input[type="reset"].small,
		input[type="button"].small,
		button.small,
		.button.small {
			font-size: 0.6rem;
			height: 3.325em;
			line-height: 3.325em;
			border-radius: 3.325em;
			padding: 0 2em;
		}

		input[type="submit"].large,
		input[type="reset"].large,
		input[type="button"].large,
		button.large,
		.button.large {
			font-size: 0.8rem;
			height: 4em;
			line-height: 4em;
			border-radius: 4em;
			padding: 0 3em;
		}

		input[type="submit"].wide,
		input[type="reset"].wide,
		input[type="button"].wide,
		button.wide,
		.button.wide {
			min-width: 14em;
		}

		input[type="submit"].disabled, input[type="submit"]:disabled,
		input[type="reset"].disabled,
		input[type="reset"]:disabled,
		input[type="button"].disabled,
		input[type="button"]:disabled,
		button.disabled,
		button:disabled,
		.button.disabled,
		.button:disabled {
			pointer-events: none;
			opacity: 0.25;
		}

	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	.button {
		background-color: transparent;
		box-shadow: inset 0 0 0 1px rgba(0, 0, 0, 0.2);
		color: #000000 !important;
	}

		input[type="submit"]:hover,
		input[type="reset"]:hover,
		input[type="button"]:hover,
		button:hover,
		.button:hover {
			box-shadow: inset 0 0 0 1px #47D3E5;
			color: #47D3E5 !important;
		}

		input[type="submit"]:active,
		input[type="reset"]:active,
		input[type="button"]:active,
		button:active,
		.button:active {
			background-color: rgba(71, 211, 229, 0.2);
			box-shadow: inset 0 0 0 1px #47D3E5;
			color: #47D3E5 !important;
		}

		input[type="submit"].primary,
		input[type="reset"].primary,
		input[type="button"].primary,
		button.primary,
		.button.primary {
			background-color: #000000;
			box-shadow: none;
			color: #ffffff !important;
		}

			input[type="submit"].primary:hover,
			input[type="reset"].primary:hover,
			input[type="button"].primary:hover,
			button.primary:hover,
			.button.primary:hover {
				background-color: #47D3E5;
			}

			input[type="submit"].primary:active,
			input[type="reset"].primary:active,
			input[type="button"].primary:active,
			button.primary:active,
			.button.primary:active {
				background-color: #1ebdd1;
			}

/* Form */

	form {
		margin: 0 0 2rem 0;
	}

		form > :last-child {
			margin-bottom: 0;
		}

		form > .fields {
			display: -moz-flex;
			display: -webkit-flex;
			display: -ms-flex;
			display: flex;
			-moz-flex-wrap: wrap;
			-webkit-flex-wrap: wrap;
			-ms-flex-wrap: wrap;
			flex-wrap: wrap;
			width: calc(100% + 3rem);
			margin: -1.5rem 0 2rem -1.5rem;
		}

			form > .fields > .field {
				-moz-flex-grow: 0;
				-webkit-flex-grow: 0;
				-ms-flex-grow: 0;
				flex-grow: 0;
				-moz-flex-shrink: 0;
				-webkit-flex-shrink: 0;
				-ms-flex-shrink: 0;
				flex-shrink: 0;
				padding: 1.5rem 0 0 1.5rem;
				width: calc(100% - 1.5rem);
			}

				form > .fields > .field.half {
					width: calc(50% - 0.75rem);
				}

				form > .fields > .field.third {
					width: calc(100%/3 - 0.5rem);
				}

				form > .fields > .field.quarter {
					width: calc(25% - 0.375rem);
				}

		@media screen and (max-width: 480px) {

			form > .fields {
				width: calc(100% + 3rem);
				margin: -1.5rem 0 2rem -1.5rem;
			}

				form > .fields > .field {
					padding: 1.5rem 0 0 1.5rem;
					width: calc(100% - 1.5rem);
				}

					form > .fields > .field.half {
						width: calc(100% - 1.5rem);
					}

					form > .fields > .field.third {
						width: calc(100% - 1.5rem);
					}

					form > .fields > .field.quarter {
						width: calc(100% - 1.5rem);
					}

		}

	label {
		display: block;
		font-size: 0.9rem;
		font-weight: 400;
		margin: 0 0 1rem 0;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	input[type="search"],
	input[type="url"],
	select,
	textarea {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		background-color: transparent;
		border-radius: 4px;
		border: none;
		border: solid 1px;
		color: inherit;
		display: block;
		outline: 0;
		padding: 0 0.825rem;
		text-decoration: none;
		width: 100%;
	}

		input[type="text"]:invalid,
		input[type="password"]:invalid,
		input[type="email"]:invalid,
		input[type="tel"]:invalid,
		input[type="search"]:invalid,
		input[type="url"]:invalid,
		select:invalid,
		textarea:invalid {
			box-shadow: none;
		}

	select {
		background-size: 1.25rem;
		background-repeat: no-repeat;
		background-position: calc(100% - 1rem) center;
		height: 2.75rem;
		padding-right: 2.75rem;
		text-overflow: ellipsis;
	}

		select:focus::-ms-value {
			background-color: transparent;
		}

		select::-ms-expand {
			display: none;
		}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	input[type="search"],
	input[type="url"],
	select {
		height: 2.75rem;
	}

	textarea {
		padding: 0.75rem 1rem;
	}

	input[type="checkbox"],
	input[type="radio"] {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		display: block;
		float: left;
		margin-right: -2rem;
		opacity: 0;
		width: 1rem;
		z-index: -1;
	}

		input[type="checkbox"] + label,
		input[type="radio"] + label {
			text-decoration: none;
			-moz-user-select: none;
			-webkit-user-select: none;
			-ms-user-select: none;
			user-select: none;
			cursor: pointer;
			display: inline-block;
			font-size: 1rem;
			font-weight: 300;
			padding-left: 2.4rem;
			padding-right: 0.75rem;
			position: relative;
			margin-bottom: 0;
		}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				display: inline-block;
				font-style: normal;
				font-variant: normal;
				text-rendering: auto;
				line-height: 1;
				text-transform: none !important;
				font-family: 'Font Awesome 5 Free';
				font-weight: 900;
			}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				border-radius: 4px;
				border: solid 1px;
				content: '';
				display: inline-block;
				font-size: 0.8rem;
				height: 1.65rem;
				left: 0;
				line-height: 1.65rem;
				position: absolute;
				text-align: center;
				top: 0;
				width: 1.65rem;
			}

		input[type="checkbox"]:checked + label:before,
		input[type="radio"]:checked + label:before {
			content: '\f00c';
		}

	input[type="checkbox"] + label:before {
		border-radius: 4px;
	}

	input[type="radio"] + label:before {
		border-radius: 100%;
	}

	::-webkit-input-placeholder {
		opacity: 1.0;
	}

	:-moz-placeholder {
		opacity: 1.0;
	}

	::-moz-placeholder {
		opacity: 1.0;
	}

	:-ms-input-placeholder {
		opacity: 1.0;
	}

	label {
		color: #000000;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	input[type="search"],
	input[type="url"],
	select,
	textarea {
		border-color: rgba(0, 0, 0, 0.2);
	}

		input[type="text"]:focus,
		input[type="password"]:focus,
		input[type="email"]:focus,
		input[type="tel"]:focus,
		input[type="search"]:focus,
		input[type="url"]:focus,
		select:focus,
		textarea:focus {
			border-color: #47D3E5;
			box-shadow: 0 0 0 1px #47D3E5;
		}

	select {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='40' height='40' preserveAspectRatio='none' viewBox='0 0 40 40'%3E%3Cpath d='M9.4,12.3l10.4,10.4l10.4-10.4c0.2-0.2,0.5-0.4,0.9-0.4c0.3,0,0.6,0.1,0.9,0.4l3.3,3.3c0.2,0.2,0.4,0.5,0.4,0.9 c0,0.4-0.1,0.6-0.4,0.9L20.7,31.9c-0.2,0.2-0.5,0.4-0.9,0.4c-0.3,0-0.6-0.1-0.9-0.4L4.3,17.3c-0.2-0.2-0.4-0.5-0.4-0.9 c0-0.4,0.1-0.6,0.4-0.9l3.3-3.3c0.2-0.2,0.5-0.4,0.9-0.4S9.1,12.1,9.4,12.3z' fill='rgba(0, 0, 0, 0.2)' /%3E%3C/svg%3E");
	}

		select option {
			color: #000000;
			background: #ffffff;
		}

	input[type="checkbox"] + label,
	input[type="radio"] + label {
		color: #000000;
	}

		input[type="checkbox"] + label:before,
		input[type="radio"] + label:before {
			border-color: rgba(0, 0, 0, 0.2);
		}

	input[type="checkbox"]:checked + label:before,
	input[type="radio"]:checked + label:before {
		background-color: #000000;
		border-color: #000000;
		color: #ffffff;
	}

	input[type="checkbox"]:focus + label:before,
	input[type="radio"]:focus + label:before {
		border-color: #47D3E5;
		box-shadow: 0 0 0 1px #47D3E5;
	}

	::-webkit-input-placeholder {
		color: rgba(0, 0, 0, 0.75) !important;
	}

	:-moz-placeholder {
		color: rgba(0, 0, 0, 0.75) !important;
	}

	::-moz-placeholder {
		color: rgba(0, 0, 0, 0.75) !important;
	}

	:-ms-input-placeholder {
		color: rgba(0, 0, 0, 0.75) !important;
	}

/* Icon */

	.icon {
		text-decoration: none;
		border-bottom: none;
		position: relative;
		text-align: center;
	}

		.icon:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			display: inline-block;
			font-style: normal;
			font-variant: normal;
			text-rendering: auto;
			line-height: 1;
			text-transform: none !important;
			font-family: 'Font Awesome 5 Free';
			font-weight: 400;
		}

		.icon > .label {
			display: none;
		}

		.icon:before {
			line-height: inherit;
		}

		.icon.solid:before {
			font-weight: 900;
		}

		.icon.brands:before {
			font-family: 'Font Awesome 5 Brands';
		}

		.icon.style2:before {
			border-radius: 2.75em;
			display: inline-block;
			height: 2.75em;
			line-height: 2.75em;
			width: 2.75em;
		}

		.icon.major {
			display: block;
			margin: 0 0 1rem 0;
		}

			.icon.major:before {
				font-size: 1.25rem;
			}

	a.icon.style2:before {
		-moz-transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
	}

	.icon.style2:before {
		box-shadow: inset 0 0 0 1px rgba(0, 0, 0, 0.2);
	}

	a.icon.style2:hover:before {
		box-shadow: inset 0 0 0 1px #47D3E5;
		color: #47D3E5;
	}

	a.icon.style2:active:before {
		background-color: rgba(71, 211, 229, 0.1);
		box-shadow: inset 0 0 0 1px #47D3E5;
		color: #47D3E5;
	}

/* Image */

	.image {
		border: 0;
		border-radius: 4px;
		display: inline-block;
		position: relative;
	}

		.image img {
			display: block;
			border-radius: 4px;
		}

		.image.left, .image.right {
			width: 40%;
			max-width: 10rem;
		}

			.image.left img, .image.right img {
				width: 100%;
			}

		.image.left {
			float: left;
			margin: 0 1.5rem 1rem 0;
			top: 0.25rem;
		}

		.image.right {
			float: right;
			margin: 0 0 1rem 1.5rem;
			top: 0.25rem;
		}

		.image.fit {
			display: block;
			margin: 0 0 2rem 0;
			width: 100%;
		}

			.image.fit img {
				width: 100%;
			}

		.image.main {
			display: block;
			margin: 0 0 3rem 0;
			width: 100%;
		}

			.image.main img {
				width: 100%;
			}

/* List */

	ol {
		list-style: decimal;
		margin: 0 0 2rem 0;
		padding-left: 1.25rem;
	}

		ol li {
			padding-left: 0.25rem;
		}

	ul {
		list-style: disc;
		margin: 0 0 2rem 0;
		padding-left: 1rem;
	}

		ul li {
			padding-left: 0.5rem;
		}

		ul.alt {
			list-style: none;
			padding-left: 0;
		}

			ul.alt li {
				border-top: solid 1px;
				padding: 0.5rem 0;
			}

				ul.alt li:first-child {
					border-top: 0;
					padding-top: 0;
				}

	dl {
		margin: 0 0 2rem 0;
	}

		dl dt {
			display: block;
			font-weight: 400;
			margin: 0 0 1rem 0;
		}

		dl dd {
			margin-left: 2rem;
		}

		dl.style2 dt {
			width: 25%;
			float: left;
		}

		dl.style2 dd {
			width: 70%;
			float: left;
		}

		dl.style2:after {
			content: '';
			display: block;
			clear: both;
		}

	ul.alt li {
		border-top-color: rgba(0, 0, 0, 0.2);
	}

/* Actions */

	ul.actions {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		cursor: default;
		list-style: none;
		margin-left: -1rem;
		padding-left: 0;
	}

		ul.actions li {
			padding: 0 0 0 1rem;
			vertical-align: middle;
		}

		ul.actions.special {
			-moz-justify-content: center;
			-webkit-justify-content: center;
			-ms-justify-content: center;
			justify-content: center;
			width: 100%;
			margin-left: 0;
		}

			ul.actions.special li:first-child {
				padding-left: 0;
			}

		ul.actions.stacked {
			-moz-flex-direction: column;
			-webkit-flex-direction: column;
			-ms-flex-direction: column;
			flex-direction: column;
			margin-left: 0;
		}

			ul.actions.stacked li {
				padding: 1.3rem 0 0 0;
			}

				ul.actions.stacked li:first-child {
					padding-top: 0;
				}

		ul.actions.fit {
			width: calc(100% + 1rem);
		}

			ul.actions.fit li {
				-moz-flex-grow: 1;
				-webkit-flex-grow: 1;
				-ms-flex-grow: 1;
				flex-grow: 1;
				-moz-flex-shrink: 1;
				-webkit-flex-shrink: 1;
				-ms-flex-shrink: 1;
				flex-shrink: 1;
				width: 100%;
			}

				ul.actions.fit li > * {
					width: 100%;
				}

			ul.actions.fit.stacked {
				width: 100%;
			}

		@media screen and (max-width: 480px) {

			ul.actions:not(.fixed) {
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				margin-left: 0;
				width: 100% !important;
			}

				ul.actions:not(.fixed) li {
					-moz-flex-grow: 1;
					-webkit-flex-grow: 1;
					-ms-flex-grow: 1;
					flex-grow: 1;
					-moz-flex-shrink: 1;
					-webkit-flex-shrink: 1;
					-ms-flex-shrink: 1;
					flex-shrink: 1;
					padding: 1rem 0 0 0;
					text-align: center;
					width: 100%;
				}

					ul.actions:not(.fixed) li > * {
						width: 100%;
					}

					ul.actions:not(.fixed) li:first-child {
						padding-top: 0;
					}

					ul.actions:not(.fixed) li input[type="submit"],
					ul.actions:not(.fixed) li input[type="reset"],
					ul.actions:not(.fixed) li input[type="button"],
					ul.actions:not(.fixed) li button,
					ul.actions:not(.fixed) li .button {
						width: 100%;
					}

						ul.actions:not(.fixed) li input[type="submit"].icon:before,
						ul.actions:not(.fixed) li input[type="reset"].icon:before,
						ul.actions:not(.fixed) li input[type="button"].icon:before,
						ul.actions:not(.fixed) li button.icon:before,
						ul.actions:not(.fixed) li .button.icon:before {
							margin-left: -0.5rem;
						}

		}

/* Icons */

	ul.icons {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.icons li {
			display: inline-block;
			padding: 0 0.75rem 0 0;
		}

			ul.icons li:last-child {
				padding-right: 0;
			}

/* Section/Article */

	section.special, article.special {
		text-align: center;
	}

	header p {
		position: relative;
		margin: -0.65rem 0 1.5rem 0;
		font-style: italic;
	}

	header h1 + p {
		font-size: 1.375rem;
	}

	header h2 + p {
		font-size: 1.25rem;
	}

	header h3 + p {
		font-size: 1.1rem;
	}

	header h4 + p,
	header h5 + p,
	header h6 + p {
		font-size: 0.9rem;
	}

	header p {
		color: rgba(0, 0, 0, 0.75);
	}

/* Table */

	.table-wrapper {
		-webkit-overflow-scrolling: touch;
		margin: 0 0 2rem 0;
		overflow-x: auto;
	}

		.table-wrapper > table {
			margin-bottom: 0;
		}

	table {
		margin: 0 0 2rem 0;
		width: 100%;
	}

		table tbody tr {
			border: solid 1px;
			border-left: 0;
			border-right: 0;
		}

		table td {
			padding: 0.75rem 0.75rem;
		}

		table th {
			font-size: 0.9rem;
			font-weight: 400;
			padding: 0 0.75rem 0.75rem 0.75rem;
			text-align: left;
		}

		table thead {
			border-bottom: solid 2px;
		}

		table tfoot {
			border-top: solid 2px;
		}

		table.alt {
			border-collapse: separate;
		}

			table.alt tbody tr td {
				border: solid 1px;
				border-left-width: 0;
				border-top-width: 0;
			}

				table.alt tbody tr td:first-child {
					border-left-width: 1px;
				}

			table.alt tbody tr:first-child td {
				border-top-width: 1px;
			}

			table.alt thead {
				border-bottom: 0;
			}

			table.alt tfoot {
				border-top: 0;
			}

		table.fixed {
			table-layout: fixed;
		}

	table tbody tr {
		border-color: rgba(0, 0, 0, 0.2);
	}

		table tbody tr:nth-child(2n + 1) {
			background-color: rgba(0, 0, 0, 0.05);
		}

		table tbody tr.alt {
			background-color: rgba(0, 0, 0, 0.05) !important;
		}

	table th {
		color: #000000;
	}

	table thead {
		border-bottom-color: rgba(0, 0, 0, 0.2);
	}

	table tfoot {
		border-top-color: rgba(0, 0, 0, 0.2);
	}

	table.alt tbody tr td {
		border-color: rgba(0, 0, 0, 0.2);
	}

	table.uniform tbody tr:nth-child(2n + 1) {
		background-color: transparent;
	}

/* Banner (transitions) */

	.banner.onload-content-fade-up .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .banner.onload-content-fade-up .content {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

	.banner.onload-content-fade-down .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .banner.onload-content-fade-down .content {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

	.banner.onload-content-fade-left .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .banner.onload-content-fade-left .content {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

	.banner.onload-content-fade-right .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .banner.onload-content-fade-right .content {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

	.banner.onload-content-fade-in .content {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	body.is-preload .banner.onload-content-fade-in .content {
		opacity: 0;
	}

	.banner.onload-image-fade-up .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onload-image-fade-up .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .banner.onload-image-fade-up .image {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

		body.is-preload .banner.onload-image-fade-up .image img {
			opacity: 0;
		}

	.banner.onload-image-fade-down .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onload-image-fade-down .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .banner.onload-image-fade-down .image {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

		body.is-preload .banner.onload-image-fade-down .image img {
			opacity: 0;
		}

	.banner.onload-image-fade-left .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onload-image-fade-left .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .banner.onload-image-fade-left .image {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

		body.is-preload .banner.onload-image-fade-left .image img {
			opacity: 0;
		}

	.banner.onload-image-fade-right .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onload-image-fade-right .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .banner.onload-image-fade-right .image {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

		body.is-preload .banner.onload-image-fade-right .image img {
			opacity: 0;
		}

	.banner.onload-image-fade-in .image img {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	body.is-preload .banner.onload-image-fade-in .image img {
		opacity: 0;
	}

	.banner.onscroll-content-fade-up .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.banner.onscroll-content-fade-up.is-inactive .content {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

	.banner.onscroll-content-fade-down .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.banner.onscroll-content-fade-down.is-inactive .content {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

	.banner.onscroll-content-fade-left .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.banner.onscroll-content-fade-left.is-inactive .content {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

	.banner.onscroll-content-fade-right .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.banner.onscroll-content-fade-right.is-inactive .content {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

	.banner.onscroll-content-fade-in .content {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	.banner.onscroll-content-fade-in.is-inactive .content {
		opacity: 0;
	}

	.banner.onscroll-image-fade-up .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onscroll-image-fade-up .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.banner.onscroll-image-fade-up.is-inactive .image {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

		.banner.onscroll-image-fade-up.is-inactive .image img {
			opacity: 0;
		}

	.banner.onscroll-image-fade-down .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onscroll-image-fade-down .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.banner.onscroll-image-fade-down.is-inactive .image {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

		.banner.onscroll-image-fade-down.is-inactive .image img {
			opacity: 0;
		}

	.banner.onscroll-image-fade-left .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onscroll-image-fade-left .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.banner.onscroll-image-fade-left.is-inactive .image {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

		.banner.onscroll-image-fade-left.is-inactive .image img {
			opacity: 0;
		}

	.banner.onscroll-image-fade-right .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.banner.onscroll-image-fade-right .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.banner.onscroll-image-fade-right.is-inactive .image {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

		.banner.onscroll-image-fade-right.is-inactive .image img {
			opacity: 0;
		}

	.banner.onscroll-image-fade-in .image img {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	.banner.onscroll-image-fade-in.is-inactive .image img {
		opacity: 0;
	}

/* Banner (style1) */

	.banner.style1 {
		-moz-align-items: -moz-stretch;
		-webkit-align-items: -webkit-stretch;
		-ms-align-items: -ms-stretch;
		align-items: stretch;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row;
		-webkit-flex-direction: row;
		-ms-flex-direction: row;
		flex-direction: row;
		-moz-justify-content: -moz-flex-end;
		-webkit-justify-content: -webkit-flex-end;
		-ms-justify-content: -ms-flex-end;
		justify-content: flex-end;
		position: relative;
		text-align: left;
		overflow-x: hidden;
	}

		.banner.style1 .content {
			padding: 7rem 7rem 5rem 7rem ;
			-moz-align-self: center;
			-webkit-align-self: center;
			-ms-align-self: center;
			align-self: center;
			-moz-flex-grow: 1;
			-webkit-flex-grow: 1;
			-ms-flex-grow: 1;
			flex-grow: 1;
			-moz-flex-shrink: 1;
			-webkit-flex-shrink: 1;
			-ms-flex-shrink: 1;
			flex-shrink: 1;
			width: 50%;
			max-width: 48rem;
			margin: 0 auto;
		}

		.banner.style1 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			border-radius: 0;
			width: 50%;
		}

			.banner.style1 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

		@media screen and (max-width: 1680px) {

			.banner.style1 .content {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.banner.style1 .content {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.banner.style1 .content {
				padding: 3.75rem 3rem 1.75rem 3rem ;
			}

		}

		@media screen and (max-width: 736px) {

			.banner.style1 .content {
				padding: 2.5rem 2rem 0.5rem 2rem ;
			}

		}

		@media screen and (orientation: portrait) {

			.banner.style1 {
				-moz-flex-direction: column-reverse;
				-webkit-flex-direction: column-reverse;
				-ms-flex-direction: column-reverse;
				flex-direction: column-reverse;
				text-align: center;
			}

				.banner.style1 .content {
					display: -moz-flex;
					display: -webkit-flex;
					display: -ms-flex;
					display: flex;
					-moz-flex-direction: column;
					-webkit-flex-direction: column;
					-ms-flex-direction: column;
					flex-direction: column;
					-moz-justify-content: center;
					-webkit-justify-content: center;
					-ms-justify-content: center;
					justify-content: center;
					width: 100%;
					max-width: 100%;
				}

				.banner.style1 .image {
					width: 100%;
					max-width: 100%;
					height: 45vh;
				}

		}

		.banner.style1.fullscreen {
			min-height: 100vh;
		}

			@media screen and (orientation: portrait) {

				.banner.style1.fullscreen .content {
					min-height: 50vh;
				}

				.banner.style1.fullscreen .image {
					height: 50vh;
				}

			}

		.banner.style1.orient-right {
			-moz-flex-direction: row-reverse;
			-webkit-flex-direction: row-reverse;
			-ms-flex-direction: row-reverse;
			flex-direction: row-reverse;
		}

			@media screen and (orientation: portrait) {

				.banner.style1.orient-right {
					-moz-flex-direction: column-reverse;
					-webkit-flex-direction: column-reverse;
					-ms-flex-direction: column-reverse;
					flex-direction: column-reverse;
				}

			}

		.banner.style1.content-align-center {
			text-align: center;
		}

		.banner.style1.content-align-right {
			text-align: right;
		}

			@media screen and (orientation: portrait) {

				.banner.style1.content-align-right {
					text-align: center;
				}

			}

		.banner.style1.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.banner.style1.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Banner (style2) */

	.banner.style2 {
		padding: 5.25rem 5.25rem 3.25rem 5.25rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		background-color: inherit;
		position: relative;
		text-align: center;
		overflow-x: hidden;
	}

		.banner.style2 .content {
			padding: 5.25rem 5.25rem 3.25rem 5.25rem ;
			position: relative;
			width: 40rem;
			max-width: 100%;
			background-color: inherit;
			border-radius: 0.5rem;
			margin-bottom: 2rem;
			z-index: 1;
		}

		.banner.style2 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			position: absolute;
			width: 100%;
			height: 100%;
			top: 0;
			left: 0;
			border-radius: 0;
		}

			.banner.style2 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

		@media screen and (max-width: 1680px) {

			.banner.style2 {
				padding: 3.75rem 3.75rem 1.75rem 3.75rem ;
			}

				.banner.style2 .content {
					padding: 3.75rem 3.75rem 1.75rem 3.75rem ;
				}

		}

		@media screen and (max-width: 1280px) {

			.banner.style2 {
				padding: 4rem 3rem 2rem 3rem ;
			}

				.banner.style2 .content {
					padding: 4rem 3rem 2rem 3rem ;
				}

		}

		@media screen and (max-width: 980px) {

			.banner.style2 {
				padding: 3rem 3rem 1rem 3rem ;
			}

				.banner.style2 .content {
					padding: 3.75rem 2.25rem 1.75rem 2.25rem ;
				}

		}

		@media screen and (max-width: 736px) {

			.banner.style2 {
				padding: 2rem 2rem 0.1rem 2rem ;
			}

				.banner.style2 .content {
					padding: 2.5rem 1.5rem 0.5rem 1.5rem ;
				}

		}

		.banner.style2.fullscreen {
			min-height: 100vh;
		}

		.banner.style2.orient-left {
			-moz-justify-content: -moz-flex-start;
			-webkit-justify-content: -webkit-flex-start;
			-ms-justify-content: -ms-flex-start;
			justify-content: flex-start;
			padding-left: 0;
		}

			.banner.style2.orient-left .content {
				border-top-left-radius: 0;
				border-bottom-left-radius: 0;
			}

		.banner.style2.orient-right {
			-moz-justify-content: -moz-flex-end;
			-webkit-justify-content: -webkit-flex-end;
			-ms-justify-content: -ms-flex-end;
			justify-content: flex-end;
			padding-right: 0;
		}

			.banner.style2.orient-right .content {
				border-top-right-radius: 0;
				border-bottom-right-radius: 0;
			}

		.banner.style2.content-align-left {
			text-align: left;
		}

		.banner.style2.content-align-right {
			text-align: right;
		}

		.banner.style2.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.banner.style2.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Banner (style3) */

	.banner.style3 {
		padding: 7rem 7rem 5rem 7rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row-reverse;
		-webkit-flex-direction: row-reverse;
		-ms-flex-direction: row-reverse;
		flex-direction: row-reverse;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		position: relative;
		text-align: left;
		overflow-x: hidden;
	}

		.banner.style3 .content {
			width: 31.5rem;
			max-width: 100%;
		}

		.banner.style3 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			width: 21rem;
			height: 21rem;
			border-radius: 100%;
			margin: 0 3.5rem 2rem 0;
		}

			.banner.style3 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				width: 100%;
				height: 100%;
				border-radius: 100%;
			}

		@media screen and (max-width: 1680px) {

			.banner.style3 {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.banner.style3 {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.banner.style3 {
				padding: 3.75rem 3rem 1.75rem 3rem ;
			}

				.banner.style3 .image {
					width: 18.375rem;
					height: 18.375rem;
				}

		}

		@media screen and (max-width: 736px) {

			.banner.style3 {
				padding: 2.5rem 2rem 0.5rem 2rem ;
				-moz-align-items: -moz-flex-start;
				-webkit-align-items: -webkit-flex-start;
				-ms-align-items: -ms-flex-start;
				align-items: flex-start;
			}

				.banner.style3 .image {
					width: 15.75rem;
					height: 15.75rem;
					margin: 0 2rem 2rem 0;
				}

		}

		@media screen and (orientation: portrait) {

			.banner.style3 {
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				-moz-flex-direction: column-reverse;
				-webkit-flex-direction: column-reverse;
				-ms-flex-direction: column-reverse;
				flex-direction: column-reverse;
				text-align: center;
			}

				.banner.style3 .content {
					width: 34rem;
					max-width: 100%;
				}

				.banner.style3 .image {
					margin-right: 0;
				}

		}

		.banner.style3.fullscreen {
			min-height: 100vh;
		}

		.banner.style3.orient-left {
			-moz-flex-direction: row;
			-webkit-flex-direction: row;
			-ms-flex-direction: row;
			flex-direction: row;
		}

			.banner.style3.orient-left .image {
				margin: 0 0 2rem 3.5rem;
			}

			@media screen and (max-width: 736px) {

				.banner.style3.orient-left .image {
					margin: 0 0 2rem 2rem;
				}

			}

			@media screen and (orientation: portrait) {

				.banner.style3.orient-left {
					-moz-flex-direction: column-reverse;
					-webkit-flex-direction: column-reverse;
					-ms-flex-direction: column-reverse;
					flex-direction: column-reverse;
				}

					.banner.style3.orient-left .image {
						margin-left: 0;
					}

			}

		.banner.style3.content-align-center {
			text-align: center;
		}

		.banner.style3.content-align-right {
			text-align: right;
		}

		.banner.style3.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.banner.style3.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Banner (style4) */

	.banner.style4 {
		padding: 7rem 7rem 5rem 7rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row-reverse;
		-webkit-flex-direction: row-reverse;
		-ms-flex-direction: row-reverse;
		flex-direction: row-reverse;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		position: relative;
		text-align: left;
		overflow-x: hidden;
	}

		.banner.style4 .content {
			width: 31.5rem;
			max-width: 100%;
		}

		.banner.style4 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			border-radius: 0;
			border: solid 1px;
			width: 13rem;
			height: 23.11111rem;
			margin-top: 2.5rem;
			margin-bottom: 5rem;
			margin-right: 3.5rem;
		}

			.banner.style4 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

			.banner.style4 .image:before {
				content: '';
				display: block;
				background-position: center;
				background-repeat: no-repeat;
				border: solid 1px;
				border-bottom: 0;
			}

			.banner.style4 .image:after {
				content: '';
				display: block;
				background-position: center;
				background-repeat: no-repeat;
				border: solid 1px;
				border-top: 0;
			}

			.banner.style4 .image:before {
				height: 2.5rem;
				background-size: 64px 32px;
				margin-top: -2.5rem;
				border-radius: 1rem 1rem 0 0;
			}

			.banner.style4 .image:after {
				height: 3rem;
				background-size: 64px 32px;
				margin-bottom: -3rem;
				border-radius: 0 0 1rem 1rem;
			}

		@media screen and (max-width: 1680px) {

			.banner.style4 {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.banner.style4 {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.banner.style4 {
				padding: 3.75rem 3rem 1.75rem 3rem ;
			}

				.banner.style4 .image {
					width: 11.375rem;
					height: 20.22222rem;
					margin-top: 2.1875rem;
					margin-bottom: 4.625rem;
				}

					.banner.style4 .image:before {
						height: 2.1875rem;
						background-size: 56px 28px;
						margin-top: -2.1875rem;
						border-radius: 0.875rem 0.875rem 0 0;
					}

					.banner.style4 .image:after {
						height: 2.625rem;
						background-size: 56px 28px;
						margin-bottom: -2.625rem;
						border-radius: 0 0 0.875rem 0.875rem;
					}

		}

		@media screen and (max-width: 736px) {

			.banner.style4 {
				padding: 2.5rem 2rem 0.5rem 2rem ;
				-moz-align-items: -moz-flex-start;
				-webkit-align-items: -webkit-flex-start;
				-ms-align-items: -ms-flex-start;
				align-items: flex-start;
			}

				.banner.style4 .image {
					width: 8.125rem;
					height: 14.44444rem;
					margin-top: 1.5625rem;
					margin-bottom: 3.875rem;
				}

					.banner.style4 .image:before {
						height: 1.5625rem;
						background-size: 40px 20px;
						margin-top: -1.5625rem;
						border-radius: 0.625rem 0.625rem 0 0;
					}

					.banner.style4 .image:after {
						height: 1.875rem;
						background-size: 40px 20px;
						margin-bottom: -1.875rem;
						border-radius: 0 0 0.625rem 0.625rem;
					}

		}

		@media screen and (orientation: portrait) {

			.banner.style4 {
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				-moz-flex-direction: column-reverse;
				-webkit-flex-direction: column-reverse;
				-ms-flex-direction: column-reverse;
				flex-direction: column-reverse;
				text-align: center;
			}

				.banner.style4 .content {
					width: 34rem;
					max-width: 100%;
				}

				.banner.style4 .image {
					margin-right: 0;
					margin-left: 0;
				}

		}

		.banner.style4.fullscreen {
			min-height: 100vh;
		}

		.banner.style4.orient-left {
			-moz-flex-direction: row;
			-webkit-flex-direction: row;
			-ms-flex-direction: row;
			flex-direction: row;
		}

			.banner.style4.orient-left .image {
				margin-right: 0;
				margin-left: 3.5rem;
			}

			@media screen and (orientation: portrait) {

				.banner.style4.orient-left {
					-moz-flex-direction: column-reverse;
					-webkit-flex-direction: column-reverse;
					-ms-flex-direction: column-reverse;
					flex-direction: column-reverse;
				}

					.banner.style4.orient-left .image {
						margin-right: 0;
						margin-left: 0;
					}

			}

		.banner.style4.content-align-center {
			text-align: center;
		}

		.banner.style4.content-align-right {
			text-align: right;
		}

		.banner.style4.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.banner.style4.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Banner (style5) */

	.banner.style5 {
		padding: 7rem 7rem 5rem 7rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		background-color: inherit;
		position: relative;
		text-align: center;
		overflow-x: hidden;
	}

		.banner.style5 .content {
			position: relative;
			width: 40rem;
			max-width: 100%;
			margin-bottom: 2rem;
			z-index: 1;
		}

		.banner.style5 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			position: absolute;
			width: 100%;
			height: 100%;
			top: 0;
			left: 0;
			border-radius: 0;
			opacity: 0.5;
		}

			.banner.style5 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

		@media screen and (max-width: 1680px) {

			.banner.style5 {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.banner.style5 {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.banner.style5 {
				padding: 3.75rem 3rem 1.75rem 3rem ;
			}

		}

		@media screen and (max-width: 736px) {

			.banner.style5 {
				padding: 2.5rem 2rem 0.5rem 2rem ;
			}

		}

		.banner.style5.fullscreen {
			min-height: 100vh;
		}

		.banner.style5.content-align-left {
			text-align: left;
		}

		.banner.style5.content-align-right {
			text-align: right;
		}

		.banner.style5.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.banner.style5.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

	.banner .image {
		background-color: rgba(0, 0, 0, 0.125);
	}

	.banner.invert .image {
		background-color: rgba(255, 255, 255, 0.125);
	}

	.banner.style4 .image {
		border-color: rgba(0, 0, 0, 0.2);
		background-color: rgba(0, 0, 0, 0.2);
		border-width: 0;
	}

		.banner.style4 .image:before {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: rgba(0, 0, 0, 0.2)%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='11' y='12' width='42' height='8' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: rgba(0, 0, 0, 0.2);
			width: 100%;
		}

		.banner.style4 .image:after {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: rgba(0, 0, 0, 0.2)%3B stroke-width: 1px%3B %7D%3C/style%3E%3Ccircle cx='32' cy='16' r='14' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: rgba(0, 0, 0, 0.2);
			width: 100%;
		}

	.banner.style4.android .image:after {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: rgba(0, 0, 0, 0.2)%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='6' y='4' width='52' height='24' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
	}

	.banner.style4.invert .image {
		border-color: white;
		background-color: white;
		border-width: 1px;
	}

		.banner.style4.invert .image:before {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='11' y='12' width='42' height='8' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: white;
			width: calc(100% + 2px);
			margin-left: -1px;
		}

		.banner.style4.invert .image:after {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Ccircle cx='32' cy='16' r='14' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: white;
			width: calc(100% + 2px);
			margin-left: -1px;
		}

	.banner.style4.invert.android .image:after {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='6' y='4' width='52' height='24' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
	}

/* Spotlight (transitions) */

	.spotlight.onload-content-fade-up .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .spotlight.onload-content-fade-up .content {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

	.spotlight.onload-content-fade-down .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .spotlight.onload-content-fade-down .content {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

	.spotlight.onload-content-fade-left .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .spotlight.onload-content-fade-left .content {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

	.spotlight.onload-content-fade-right .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	body.is-preload .spotlight.onload-content-fade-right .content {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

	.spotlight.onload-content-fade-in .content {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	body.is-preload .spotlight.onload-content-fade-in .content {
		opacity: 0;
	}

	.spotlight.onload-image-fade-up .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onload-image-fade-up .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .spotlight.onload-image-fade-up .image {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

		body.is-preload .spotlight.onload-image-fade-up .image img {
			opacity: 0;
		}

	.spotlight.onload-image-fade-down .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onload-image-fade-down .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .spotlight.onload-image-fade-down .image {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

		body.is-preload .spotlight.onload-image-fade-down .image img {
			opacity: 0;
		}

	.spotlight.onload-image-fade-left .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onload-image-fade-left .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .spotlight.onload-image-fade-left .image {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

		body.is-preload .spotlight.onload-image-fade-left .image img {
			opacity: 0;
		}

	.spotlight.onload-image-fade-right .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onload-image-fade-right .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	body.is-preload .spotlight.onload-image-fade-right .image {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

		body.is-preload .spotlight.onload-image-fade-right .image img {
			opacity: 0;
		}

	.spotlight.onload-image-fade-in .image img {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	body.is-preload .spotlight.onload-image-fade-in .image img {
		opacity: 0;
	}

	.spotlight.onscroll-content-fade-up .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.spotlight.onscroll-content-fade-up.is-inactive .content {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

	.spotlight.onscroll-content-fade-down .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.spotlight.onscroll-content-fade-down.is-inactive .content {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

	.spotlight.onscroll-content-fade-left .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.spotlight.onscroll-content-fade-left.is-inactive .content {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

	.spotlight.onscroll-content-fade-right .content {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

	.spotlight.onscroll-content-fade-right.is-inactive .content {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

	.spotlight.onscroll-content-fade-in .content {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	.spotlight.onscroll-content-fade-in.is-inactive .content {
		opacity: 0;
	}

	.spotlight.onscroll-image-fade-up .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onscroll-image-fade-up .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.spotlight.onscroll-image-fade-up.is-inactive .image {
		-moz-transform: translateY(1rem);
		-webkit-transform: translateY(1rem);
		-ms-transform: translateY(1rem);
		transform: translateY(1rem);
		opacity: 0;
	}

		.spotlight.onscroll-image-fade-up.is-inactive .image img {
			opacity: 0;
		}

	.spotlight.onscroll-image-fade-down .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onscroll-image-fade-down .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.spotlight.onscroll-image-fade-down.is-inactive .image {
		-moz-transform: translateY(-1rem);
		-webkit-transform: translateY(-1rem);
		-ms-transform: translateY(-1rem);
		transform: translateY(-1rem);
		opacity: 0;
	}

		.spotlight.onscroll-image-fade-down.is-inactive .image img {
			opacity: 0;
		}

	.spotlight.onscroll-image-fade-left .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onscroll-image-fade-left .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.spotlight.onscroll-image-fade-left.is-inactive .image {
		-moz-transform: translateX(1rem);
		-webkit-transform: translateX(1rem);
		-ms-transform: translateX(1rem);
		transform: translateX(1rem);
		opacity: 0;
	}

		.spotlight.onscroll-image-fade-left.is-inactive .image img {
			opacity: 0;
		}

	.spotlight.onscroll-image-fade-right .image {
		-moz-transition: opacity 0.75s ease-in-out, -moz-transform 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out, -webkit-transform 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out, -ms-transform 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out, transform 0.75s ease-in-out;
	}

		.spotlight.onscroll-image-fade-right .image img {
			-moz-transition: opacity 0.75s ease-in-out;
			-webkit-transition: opacity 0.75s ease-in-out;
			-ms-transition: opacity 0.75s ease-in-out;
			transition: opacity 0.75s ease-in-out;
			-moz-transition-delay: 0.5625s;
			-webkit-transition-delay: 0.5625s;
			-ms-transition-delay: 0.5625s;
			transition-delay: 0.5625s;
		}

	.spotlight.onscroll-image-fade-right.is-inactive .image {
		-moz-transform: translateX(-1rem);
		-webkit-transform: translateX(-1rem);
		-ms-transform: translateX(-1rem);
		transform: translateX(-1rem);
		opacity: 0;
	}

		.spotlight.onscroll-image-fade-right.is-inactive .image img {
			opacity: 0;
		}

	.spotlight.onscroll-image-fade-in .image img {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
	}

	.spotlight.onscroll-image-fade-in.is-inactive .image img {
		opacity: 0;
	}

/* Spotlight (style1) */

	.spotlight.style1 {
		-moz-align-items: -moz-stretch;
		-webkit-align-items: -webkit-stretch;
		-ms-align-items: -ms-stretch;
		align-items: stretch;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row;
		-webkit-flex-direction: row;
		-ms-flex-direction: row;
		flex-direction: row;
		-moz-justify-content: -moz-flex-end;
		-webkit-justify-content: -webkit-flex-end;
		-ms-justify-content: -ms-flex-end;
		justify-content: flex-end;
		position: relative;
		overflow-x: hidden;
		text-align: left;
	}

		.spotlight.style1 .content {
			padding: 7rem 7rem 5rem 7rem ;
			-moz-align-self: center;
			-webkit-align-self: center;
			-ms-align-self: center;
			align-self: center;
			-moz-flex-grow: 1;
			-webkit-flex-grow: 1;
			-ms-flex-grow: 1;
			flex-grow: 1;
			-moz-flex-shrink: 1;
			-webkit-flex-shrink: 1;
			-ms-flex-shrink: 1;
			flex-shrink: 1;
			width: 65%;
			max-width: 64rem;
			margin: 0 auto;
		}

		.spotlight.style1 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			width: 35%;
			min-width: 25rem;
			border-radius: 0;
		}

			.spotlight.style1 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

		@media screen and (max-width: 1680px) {

			.spotlight.style1 .content {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.spotlight.style1 .content {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.spotlight.style1 .content {
				padding: 3.75rem 3rem 1.75rem 3rem ;
				width: 50%;
				min-width: 0;
			}

			.spotlight.style1 .image {
				width: 50%;
				min-width: 0;
			}

		}

		@media screen and (max-width: 736px) {

			.spotlight.style1 .content {
				padding: 2.5rem 2rem 0.5rem 2rem ;
			}

		}

	@media screen and (max-width: 736px) and (orientation: portrait) {

		.spotlight.style1 {
			-moz-flex-direction: column-reverse;
			-webkit-flex-direction: column-reverse;
			-ms-flex-direction: column-reverse;
			flex-direction: column-reverse;
			text-align: center !important;
		}

			.spotlight.style1 .content {
				width: 100%;
			}

			.spotlight.style1 .image {
				width: 100%;
			}

				.spotlight.style1 .image img {
					position: relative;
				}

	}

		.spotlight.style1.orient-right {
			-moz-flex-direction: row-reverse;
			-webkit-flex-direction: row-reverse;
			-ms-flex-direction: row-reverse;
			flex-direction: row-reverse;
		}

	@media screen and (max-width: 736px) and (orientation: portrait) {

		.spotlight.style1.orient-right {
			-moz-flex-direction: column-reverse;
			-webkit-flex-direction: column-reverse;
			-ms-flex-direction: column-reverse;
			flex-direction: column-reverse;
		}

	}

		.spotlight.style1.content-align-center {
			text-align: center;
		}

		.spotlight.style1.content-align-right {
			text-align: right;
		}

		.spotlight.style1.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.spotlight.style1.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Spotlight (style2) */

	.spotlight.style2 {
		padding: 7rem 7rem 5rem 7rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row-reverse;
		-webkit-flex-direction: row-reverse;
		-ms-flex-direction: row-reverse;
		flex-direction: row-reverse;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		position: relative;
		overflow-x: hidden;
		text-align: left;
	}

		.spotlight.style2 .content {
			width: 44.5rem;
			max-width: 100%;
		}

		.spotlight.style2 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			width: 21rem;
			height: 21rem;
			border-radius: 100%;
			margin: 0 3.5rem 2rem 0;
		}

			.spotlight.style2 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				width: 100%;
				height: 100%;
				border-radius: 100%;
			}

		@media screen and (max-width: 1680px) {

			.spotlight.style2 {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.spotlight.style2 {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.spotlight.style2 {
				padding: 3.75rem 3rem 1.75rem 3rem ;
			}

				.spotlight.style2 .image {
					width: 18.375rem;
					height: 18.375rem;
				}

		}

		@media screen and (max-width: 736px) {

			.spotlight.style2 {
				padding: 2.5rem 2rem 0.5rem 2rem ;
				-moz-align-items: -moz-flex-start;
				-webkit-align-items: -webkit-flex-start;
				-ms-align-items: -ms-flex-start;
				align-items: flex-start;
			}

				.spotlight.style2 .image {
					width: 15.75rem;
					height: 15.75rem;
					margin: 0 2rem 2rem 0;
				}

		}

		@media screen and (orientation: portrait) {

			.spotlight.style2 {
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				-moz-flex-direction: column-reverse;
				-webkit-flex-direction: column-reverse;
				-ms-flex-direction: column-reverse;
				flex-direction: column-reverse;
				text-align: center !important;
			}

				.spotlight.style2 .content {
					width: 34rem;
					max-width: 100%;
				}

				.spotlight.style2 .image {
					margin-right: 0;
				}

		}

		.spotlight.style2.orient-left {
			-moz-flex-direction: row;
			-webkit-flex-direction: row;
			-ms-flex-direction: row;
			flex-direction: row;
		}

			.spotlight.style2.orient-left .image {
				margin: 0 0 2rem 3.5rem;
			}

			@media screen and (max-width: 736px) {

				.spotlight.style2.orient-left .image {
					margin: 0 0 2rem 2rem;
				}

			}

			@media screen and (orientation: portrait) {

				.spotlight.style2.orient-left {
					-moz-flex-direction: column-reverse;
					-webkit-flex-direction: column-reverse;
					-ms-flex-direction: column-reverse;
					flex-direction: column-reverse;
				}

					.spotlight.style2.orient-left .image {
						margin-left: 0;
					}

			}

		.spotlight.style2.content-align-center {
			text-align: center;
		}

		.spotlight.style2.content-align-right {
			text-align: right;
		}

		.spotlight.style2.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.spotlight.style2.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Spotlight (style3) */

	.spotlight.style3 {
		padding: 7rem 7rem 5rem 7rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row-reverse;
		-webkit-flex-direction: row-reverse;
		-ms-flex-direction: row-reverse;
		flex-direction: row-reverse;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		position: relative;
		overflow-x: hidden;
		text-align: left;
	}

		.spotlight.style3 .content {
			width: 44.5rem;
			max-width: 100%;
		}

		.spotlight.style3 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			border-radius: 0;
			border: solid 1px;
			width: 13rem;
			height: 23.11111rem;
			margin-top: 2.5rem;
			margin-bottom: 5rem;
			margin-right: 3.5rem;
		}

			.spotlight.style3 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

			.spotlight.style3 .image:before {
				content: '';
				display: block;
				background-position: center;
				background-repeat: no-repeat;
				border: solid 1px;
				border-bottom: 0;
			}

			.spotlight.style3 .image:after {
				content: '';
				display: block;
				background-position: center;
				background-repeat: no-repeat;
				border: solid 1px;
				border-top: 0;
			}

			.spotlight.style3 .image:before {
				height: 2.5rem;
				background-size: 64px 32px;
				margin-top: -2.5rem;
				border-radius: 1rem 1rem 0 0;
			}

			.spotlight.style3 .image:after {
				height: 3rem;
				background-size: 64px 32px;
				margin-bottom: -3rem;
				border-radius: 0 0 1rem 1rem;
			}

		@media screen and (max-width: 1680px) {

			.spotlight.style3 {
				padding: 5rem 5rem 3rem 5rem ;
			}

		}

		@media screen and (max-width: 1280px) {

			.spotlight.style3 {
				padding: 4rem 4rem 2rem 4rem ;
			}

		}

		@media screen and (max-width: 980px) {

			.spotlight.style3 {
				padding: 3.75rem 3rem 1.75rem 3rem ;
			}

				.spotlight.style3 .image {
					width: 11.375rem;
					height: 20.22222rem;
					margin-top: 2.1875rem;
					margin-bottom: 4.625rem;
				}

					.spotlight.style3 .image:before {
						height: 2.1875rem;
						background-size: 56px 28px;
						margin-top: -2.1875rem;
						border-radius: 0.875rem 0.875rem 0 0;
					}

					.spotlight.style3 .image:after {
						height: 2.625rem;
						background-size: 56px 28px;
						margin-bottom: -2.625rem;
						border-radius: 0 0 0.875rem 0.875rem;
					}

		}

		@media screen and (max-width: 736px) {

			.spotlight.style3 {
				padding: 2.5rem 2rem 0.5rem 2rem ;
				-moz-align-items: -moz-flex-start;
				-webkit-align-items: -webkit-flex-start;
				-ms-align-items: -ms-flex-start;
				align-items: flex-start;
			}

				.spotlight.style3 .image {
					width: 8.125rem;
					height: 14.44444rem;
					margin-top: 1.5625rem;
					margin-bottom: 3.875rem;
				}

					.spotlight.style3 .image:before {
						height: 1.5625rem;
						background-size: 40px 20px;
						margin-top: -1.5625rem;
						border-radius: 0.625rem 0.625rem 0 0;
					}

					.spotlight.style3 .image:after {
						height: 1.875rem;
						background-size: 40px 20px;
						margin-bottom: -1.875rem;
						border-radius: 0 0 0.625rem 0.625rem;
					}

		}

		@media screen and (orientation: portrait) {

			.spotlight.style3 {
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				-moz-flex-direction: column-reverse;
				-webkit-flex-direction: column-reverse;
				-ms-flex-direction: column-reverse;
				flex-direction: column-reverse;
				text-align: center !important;
			}

				.spotlight.style3 .content {
					width: 34rem;
					max-width: 100%;
				}

				.spotlight.style3 .image {
					margin-right: 0;
					margin-left: 0;
				}

		}

		.spotlight.style3.orient-left {
			-moz-flex-direction: row;
			-webkit-flex-direction: row;
			-ms-flex-direction: row;
			flex-direction: row;
		}

			.spotlight.style3.orient-left .image {
				margin-right: 0;
				margin-left: 3.5rem;
			}

			@media screen and (orientation: portrait) {

				.spotlight.style3.orient-left {
					-moz-flex-direction: column-reverse;
					-webkit-flex-direction: column-reverse;
					-ms-flex-direction: column-reverse;
					flex-direction: column-reverse;
				}

					.spotlight.style3.orient-left .image {
						margin-right: 0;
						margin-left: 0;
					}

			}

		.spotlight.style3.content-align-center {
			text-align: center;
		}

		.spotlight.style3.content-align-right {
			text-align: right;
		}

		.spotlight.style3.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.spotlight.style3.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Spotlight (style4) */

	.spotlight.style4 {
		padding: 7rem 5.25rem 5rem 5.25rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		background-color: inherit;
		position: relative;
		overflow-x: hidden;
		text-align: center;
	}

		.spotlight.style4 .content {
			padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
			position: relative;
			width: 40rem;
			max-width: 50%;
			background-color: inherit;
			border-radius: 0.5rem;
			margin-bottom: 2rem;
			z-index: 1;
		}

		.spotlight.style4 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			position: absolute;
			width: 100%;
			height: 100%;
			top: 0;
			left: 0;
			border-radius: 0;
		}

			.spotlight.style4 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

		@media screen and (max-width: 1680px) {

			.spotlight.style4 {
				padding: 5rem 3.75rem 3rem 3.75rem ;
			}

				.spotlight.style4 .content {
					padding: 2.5rem 2.5rem 0.5rem 2.5rem ;
				}

		}

		@media screen and (max-width: 1280px) {

			.spotlight.style4 {
				padding: 4rem 3rem 2rem 3rem ;
			}

				.spotlight.style4 .content {
					padding: 3rem 3rem 1rem 3rem ;
				}

		}

		@media screen and (max-width: 980px) {

			.spotlight.style4 {
				padding: 3rem 2.25rem 1rem 2.25rem ;
			}

				.spotlight.style4 .content {
					padding: 2.25rem 2.25rem 0.25rem 2.25rem ;
				}

		}

		@media screen and (max-width: 736px) {

			.spotlight.style4 {
				padding: 2rem 1.5rem 0.1rem 1.5rem ;
			}

				.spotlight.style4 .content {
					padding: 1.5rem 1.5rem 0.1rem 1.5rem ;
				}

		}

		@media screen and (max-width: 480px) {

			.spotlight.style4 .content {
				max-width: 80%;
			}

		}

		.spotlight.style4.fullscreen {
			min-height: 100vh;
		}

		.spotlight.style4.halfscreen {
			min-height: 50vh;
		}

		.spotlight.style4.orient-left {
			-moz-justify-content: -moz-flex-start;
			-webkit-justify-content: -webkit-flex-start;
			-ms-justify-content: -ms-flex-start;
			justify-content: flex-start;
			padding-left: 0;
		}

			.spotlight.style4.orient-left .content {
				border-top-left-radius: 0;
				border-bottom-left-radius: 0;
			}

		.spotlight.style4.orient-right {
			-moz-justify-content: -moz-flex-end;
			-webkit-justify-content: -webkit-flex-end;
			-ms-justify-content: -ms-flex-end;
			justify-content: flex-end;
			padding-right: 0;
		}

			.spotlight.style4.orient-right .content {
				border-top-right-radius: 0;
				border-bottom-right-radius: 0;
			}

		.spotlight.style4.content-align-left {
			text-align: left;
		}

		.spotlight.style4.content-align-right {
			text-align: right;
		}

		.spotlight.style4.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.spotlight.style4.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

/* Spotlight (style5) */

	.spotlight.style5 {
		padding: 7rem 5.25rem 5rem 5.25rem ;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		background-color: inherit;
		position: relative;
		overflow-x: hidden;
		text-align: center;
	}

		.spotlight.style5 .content {
			padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
			position: relative;
			width: 40rem;
			max-width: 52.5%;
			background-color: inherit;
			border-radius: 0.5rem;
			margin-bottom: 2rem;
			z-index: 1;
		}

		.spotlight.style5 .image {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			position: absolute;
			width: 100%;
			height: 100%;
			top: 0;
			left: 0;
			border-radius: 0;
		}

			.spotlight.style5 .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				-moz-object-position: center;
				-webkit-object-position: center;
				-ms-object-position: center;
				object-position: center;
				display: block;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				border-radius: 0;
			}

		@media screen and (max-width: 1680px) {

			.spotlight.style5 {
				padding: 5rem 3.75rem 3rem 3.75rem ;
			}

				.spotlight.style5 .content {
					padding: 2.5rem 2.5rem 0.5rem 2.5rem ;
				}

		}

		@media screen and (max-width: 1280px) {

			.spotlight.style5 {
				padding: 4rem 3rem 2rem 3rem ;
			}

				.spotlight.style5 .content {
					padding: 3rem 3rem 1rem 3rem ;
				}

		}

		@media screen and (max-width: 980px) {

			.spotlight.style5 {
				padding: 3rem 2.25rem 1rem 2.25rem ;
			}

				.spotlight.style5 .content {
					padding: 2.25rem 2.25rem 0.25rem 2.25rem ;
				}

		}

		@media screen and (max-width: 736px) {

			.spotlight.style5 {
				padding: 2rem 1.5rem 0.1rem 1.5rem ;
			}

				.spotlight.style5 .content {
					padding: 1.5rem 1.5rem 0.1rem 1.5rem ;
				}

		}

		@media screen and (max-width: 480px) {

			.spotlight.style5 .content {
				max-width: 80%;
			}

		}

		.spotlight.style5.fullscreen {
			min-height: 100vh;
		}

		.spotlight.style5.halfscreen {
			min-height: 50vh;
		}

		.spotlight.style5.orient-left {
			-moz-justify-content: -moz-flex-start;
			-webkit-justify-content: -webkit-flex-start;
			-ms-justify-content: -ms-flex-start;
			justify-content: flex-start;
		}

		.spotlight.style5.orient-right {
			-moz-justify-content: -moz-flex-end;
			-webkit-justify-content: -webkit-flex-end;
			-ms-justify-content: -ms-flex-end;
			justify-content: flex-end;
		}

		.spotlight.style5.content-align-left {
			text-align: left;
		}

		.spotlight.style5.content-align-right {
			text-align: right;
		}

		.spotlight.style5.image-position-left .image img {
			-moz-object-position: left;
			-webkit-object-position: left;
			-ms-object-position: left;
			object-position: left;
		}

		.spotlight.style5.image-position-right .image img {
			-moz-object-position: right;
			-webkit-object-position: right;
			-ms-object-position: right;
			object-position: right;
		}

	.spotlight .image {
		background-color: rgba(0, 0, 0, 0.125);
	}

	.spotlight.invert .image {
		background-color: rgba(255, 255, 255, 0.125);
	}

	.spotlight.style3 .image {
		border-color: rgba(0, 0, 0, 0.2);
		background-color: rgba(0, 0, 0, 0.2);
		border-width: 0;
	}

		.spotlight.style3 .image:before {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: rgba(0, 0, 0, 0.2)%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='11' y='12' width='42' height='8' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: rgba(0, 0, 0, 0.2);
			width: 100%;
		}

		.spotlight.style3 .image:after {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: rgba(0, 0, 0, 0.2)%3B stroke-width: 1px%3B %7D%3C/style%3E%3Ccircle cx='32' cy='16' r='14' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: rgba(0, 0, 0, 0.2);
			width: 100%;
		}

	.spotlight.style3.android .image:after {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: rgba(0, 0, 0, 0.2)%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='6' y='4' width='52' height='24' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
	}

	.spotlight.style3.invert .image {
		border-color: white;
		background-color: white;
		border-width: 1px;
	}

		.spotlight.style3.invert .image:before {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='11' y='12' width='42' height='8' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: white;
			width: calc(100% + 2px);
			margin-left: -1px;
		}

		.spotlight.style3.invert .image:after {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Ccircle cx='32' cy='16' r='14' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			border-color: white;
			width: calc(100% + 2px);
			margin-left: -1px;
		}

	.spotlight.style3.invert.android .image:after {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='6' y='4' width='52' height='24' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
	}

/* Gallery (transitions) */

	.gallery.onload-fade-in article .image img {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
		-moz-transition-delay: 4.8s;
		-webkit-transition-delay: 4.8s;
		-ms-transition-delay: 4.8s;
		transition-delay: 4.8s;
	}

	.gallery.onload-fade-in article:nth-child(1) .image img {
		-moz-transition-delay: 0s;
		-webkit-transition-delay: 0s;
		-ms-transition-delay: 0s;
		transition-delay: 0s;
	}

	.gallery.onload-fade-in article:nth-child(2) .image img {
		-moz-transition-delay: 0.15s;
		-webkit-transition-delay: 0.15s;
		-ms-transition-delay: 0.15s;
		transition-delay: 0.15s;
	}

	.gallery.onload-fade-in article:nth-child(3) .image img {
		-moz-transition-delay: 0.3s;
		-webkit-transition-delay: 0.3s;
		-ms-transition-delay: 0.3s;
		transition-delay: 0.3s;
	}

	.gallery.onload-fade-in article:nth-child(4) .image img {
		-moz-transition-delay: 0.45s;
		-webkit-transition-delay: 0.45s;
		-ms-transition-delay: 0.45s;
		transition-delay: 0.45s;
	}

	.gallery.onload-fade-in article:nth-child(5) .image img {
		-moz-transition-delay: 0.6s;
		-webkit-transition-delay: 0.6s;
		-ms-transition-delay: 0.6s;
		transition-delay: 0.6s;
	}

	.gallery.onload-fade-in article:nth-child(6) .image img {
		-moz-transition-delay: 0.75s;
		-webkit-transition-delay: 0.75s;
		-ms-transition-delay: 0.75s;
		transition-delay: 0.75s;
	}

	.gallery.onload-fade-in article:nth-child(7) .image img {
		-moz-transition-delay: 0.9s;
		-webkit-transition-delay: 0.9s;
		-ms-transition-delay: 0.9s;
		transition-delay: 0.9s;
	}

	.gallery.onload-fade-in article:nth-child(8) .image img {
		-moz-transition-delay: 1.05s;
		-webkit-transition-delay: 1.05s;
		-ms-transition-delay: 1.05s;
		transition-delay: 1.05s;
	}

	.gallery.onload-fade-in article:nth-child(9) .image img {
		-moz-transition-delay: 1.2s;
		-webkit-transition-delay: 1.2s;
		-ms-transition-delay: 1.2s;
		transition-delay: 1.2s;
	}

	.gallery.onload-fade-in article:nth-child(10) .image img {
		-moz-transition-delay: 1.35s;
		-webkit-transition-delay: 1.35s;
		-ms-transition-delay: 1.35s;
		transition-delay: 1.35s;
	}

	.gallery.onload-fade-in article:nth-child(11) .image img {
		-moz-transition-delay: 1.5s;
		-webkit-transition-delay: 1.5s;
		-ms-transition-delay: 1.5s;
		transition-delay: 1.5s;
	}

	.gallery.onload-fade-in article:nth-child(12) .image img {
		-moz-transition-delay: 1.65s;
		-webkit-transition-delay: 1.65s;
		-ms-transition-delay: 1.65s;
		transition-delay: 1.65s;
	}

	.gallery.onload-fade-in article:nth-child(13) .image img {
		-moz-transition-delay: 1.8s;
		-webkit-transition-delay: 1.8s;
		-ms-transition-delay: 1.8s;
		transition-delay: 1.8s;
	}

	.gallery.onload-fade-in article:nth-child(14) .image img {
		-moz-transition-delay: 1.95s;
		-webkit-transition-delay: 1.95s;
		-ms-transition-delay: 1.95s;
		transition-delay: 1.95s;
	}

	.gallery.onload-fade-in article:nth-child(15) .image img {
		-moz-transition-delay: 2.1s;
		-webkit-transition-delay: 2.1s;
		-ms-transition-delay: 2.1s;
		transition-delay: 2.1s;
	}

	.gallery.onload-fade-in article:nth-child(16) .image img {
		-moz-transition-delay: 2.25s;
		-webkit-transition-delay: 2.25s;
		-ms-transition-delay: 2.25s;
		transition-delay: 2.25s;
	}

	.gallery.onload-fade-in article:nth-child(17) .image img {
		-moz-transition-delay: 2.4s;
		-webkit-transition-delay: 2.4s;
		-ms-transition-delay: 2.4s;
		transition-delay: 2.4s;
	}

	.gallery.onload-fade-in article:nth-child(18) .image img {
		-moz-transition-delay: 2.55s;
		-webkit-transition-delay: 2.55s;
		-ms-transition-delay: 2.55s;
		transition-delay: 2.55s;
	}

	.gallery.onload-fade-in article:nth-child(19) .image img {
		-moz-transition-delay: 2.7s;
		-webkit-transition-delay: 2.7s;
		-ms-transition-delay: 2.7s;
		transition-delay: 2.7s;
	}

	.gallery.onload-fade-in article:nth-child(20) .image img {
		-moz-transition-delay: 2.85s;
		-webkit-transition-delay: 2.85s;
		-ms-transition-delay: 2.85s;
		transition-delay: 2.85s;
	}

	.gallery.onload-fade-in article:nth-child(21) .image img {
		-moz-transition-delay: 3s;
		-webkit-transition-delay: 3s;
		-ms-transition-delay: 3s;
		transition-delay: 3s;
	}

	.gallery.onload-fade-in article:nth-child(22) .image img {
		-moz-transition-delay: 3.15s;
		-webkit-transition-delay: 3.15s;
		-ms-transition-delay: 3.15s;
		transition-delay: 3.15s;
	}

	.gallery.onload-fade-in article:nth-child(23) .image img {
		-moz-transition-delay: 3.3s;
		-webkit-transition-delay: 3.3s;
		-ms-transition-delay: 3.3s;
		transition-delay: 3.3s;
	}

	.gallery.onload-fade-in article:nth-child(24) .image img {
		-moz-transition-delay: 3.45s;
		-webkit-transition-delay: 3.45s;
		-ms-transition-delay: 3.45s;
		transition-delay: 3.45s;
	}

	.gallery.onload-fade-in article:nth-child(25) .image img {
		-moz-transition-delay: 3.6s;
		-webkit-transition-delay: 3.6s;
		-ms-transition-delay: 3.6s;
		transition-delay: 3.6s;
	}

	.gallery.onload-fade-in article:nth-child(26) .image img {
		-moz-transition-delay: 3.75s;
		-webkit-transition-delay: 3.75s;
		-ms-transition-delay: 3.75s;
		transition-delay: 3.75s;
	}

	.gallery.onload-fade-in article:nth-child(27) .image img {
		-moz-transition-delay: 3.9s;
		-webkit-transition-delay: 3.9s;
		-ms-transition-delay: 3.9s;
		transition-delay: 3.9s;
	}

	.gallery.onload-fade-in article:nth-child(28) .image img {
		-moz-transition-delay: 4.05s;
		-webkit-transition-delay: 4.05s;
		-ms-transition-delay: 4.05s;
		transition-delay: 4.05s;
	}

	.gallery.onload-fade-in article:nth-child(29) .image img {
		-moz-transition-delay: 4.2s;
		-webkit-transition-delay: 4.2s;
		-ms-transition-delay: 4.2s;
		transition-delay: 4.2s;
	}

	.gallery.onload-fade-in article:nth-child(30) .image img {
		-moz-transition-delay: 4.35s;
		-webkit-transition-delay: 4.35s;
		-ms-transition-delay: 4.35s;
		transition-delay: 4.35s;
	}

	.gallery.onload-fade-in article:nth-child(31) .image img {
		-moz-transition-delay: 4.5s;
		-webkit-transition-delay: 4.5s;
		-ms-transition-delay: 4.5s;
		transition-delay: 4.5s;
	}

	.gallery.onload-fade-in article:nth-child(32) .image img {
		-moz-transition-delay: 4.65s;
		-webkit-transition-delay: 4.65s;
		-ms-transition-delay: 4.65s;
		transition-delay: 4.65s;
	}

	.gallery.onload-fade-in article:nth-child(33) .image img {
		-moz-transition-delay: 4.8s;
		-webkit-transition-delay: 4.8s;
		-ms-transition-delay: 4.8s;
		transition-delay: 4.8s;
	}

	body.is-preload .gallery.onload-fade-in article .image img {
		opacity: 0;
	}

	.gallery.onscroll-fade-in article .image img {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
		-moz-transition-delay: 4.8s;
		-webkit-transition-delay: 4.8s;
		-ms-transition-delay: 4.8s;
		transition-delay: 4.8s;
	}

	.gallery.onscroll-fade-in article:nth-child(1) .image img {
		-moz-transition-delay: 0s;
		-webkit-transition-delay: 0s;
		-ms-transition-delay: 0s;
		transition-delay: 0s;
	}

	.gallery.onscroll-fade-in article:nth-child(2) .image img {
		-moz-transition-delay: 0.15s;
		-webkit-transition-delay: 0.15s;
		-ms-transition-delay: 0.15s;
		transition-delay: 0.15s;
	}

	.gallery.onscroll-fade-in article:nth-child(3) .image img {
		-moz-transition-delay: 0.3s;
		-webkit-transition-delay: 0.3s;
		-ms-transition-delay: 0.3s;
		transition-delay: 0.3s;
	}

	.gallery.onscroll-fade-in article:nth-child(4) .image img {
		-moz-transition-delay: 0.45s;
		-webkit-transition-delay: 0.45s;
		-ms-transition-delay: 0.45s;
		transition-delay: 0.45s;
	}

	.gallery.onscroll-fade-in article:nth-child(5) .image img {
		-moz-transition-delay: 0.6s;
		-webkit-transition-delay: 0.6s;
		-ms-transition-delay: 0.6s;
		transition-delay: 0.6s;
	}

	.gallery.onscroll-fade-in article:nth-child(6) .image img {
		-moz-transition-delay: 0.75s;
		-webkit-transition-delay: 0.75s;
		-ms-transition-delay: 0.75s;
		transition-delay: 0.75s;
	}

	.gallery.onscroll-fade-in article:nth-child(7) .image img {
		-moz-transition-delay: 0.9s;
		-webkit-transition-delay: 0.9s;
		-ms-transition-delay: 0.9s;
		transition-delay: 0.9s;
	}

	.gallery.onscroll-fade-in article:nth-child(8) .image img {
		-moz-transition-delay: 1.05s;
		-webkit-transition-delay: 1.05s;
		-ms-transition-delay: 1.05s;
		transition-delay: 1.05s;
	}

	.gallery.onscroll-fade-in article:nth-child(9) .image img {
		-moz-transition-delay: 1.2s;
		-webkit-transition-delay: 1.2s;
		-ms-transition-delay: 1.2s;
		transition-delay: 1.2s;
	}

	.gallery.onscroll-fade-in article:nth-child(10) .image img {
		-moz-transition-delay: 1.35s;
		-webkit-transition-delay: 1.35s;
		-ms-transition-delay: 1.35s;
		transition-delay: 1.35s;
	}

	.gallery.onscroll-fade-in article:nth-child(11) .image img {
		-moz-transition-delay: 1.5s;
		-webkit-transition-delay: 1.5s;
		-ms-transition-delay: 1.5s;
		transition-delay: 1.5s;
	}

	.gallery.onscroll-fade-in article:nth-child(12) .image img {
		-moz-transition-delay: 1.65s;
		-webkit-transition-delay: 1.65s;
		-ms-transition-delay: 1.65s;
		transition-delay: 1.65s;
	}

	.gallery.onscroll-fade-in article:nth-child(13) .image img {
		-moz-transition-delay: 1.8s;
		-webkit-transition-delay: 1.8s;
		-ms-transition-delay: 1.8s;
		transition-delay: 1.8s;
	}

	.gallery.onscroll-fade-in article:nth-child(14) .image img {
		-moz-transition-delay: 1.95s;
		-webkit-transition-delay: 1.95s;
		-ms-transition-delay: 1.95s;
		transition-delay: 1.95s;
	}

	.gallery.onscroll-fade-in article:nth-child(15) .image img {
		-moz-transition-delay: 2.1s;
		-webkit-transition-delay: 2.1s;
		-ms-transition-delay: 2.1s;
		transition-delay: 2.1s;
	}

	.gallery.onscroll-fade-in article:nth-child(16) .image img {
		-moz-transition-delay: 2.25s;
		-webkit-transition-delay: 2.25s;
		-ms-transition-delay: 2.25s;
		transition-delay: 2.25s;
	}

	.gallery.onscroll-fade-in article:nth-child(17) .image img {
		-moz-transition-delay: 2.4s;
		-webkit-transition-delay: 2.4s;
		-ms-transition-delay: 2.4s;
		transition-delay: 2.4s;
	}

	.gallery.onscroll-fade-in article:nth-child(18) .image img {
		-moz-transition-delay: 2.55s;
		-webkit-transition-delay: 2.55s;
		-ms-transition-delay: 2.55s;
		transition-delay: 2.55s;
	}

	.gallery.onscroll-fade-in article:nth-child(19) .image img {
		-moz-transition-delay: 2.7s;
		-webkit-transition-delay: 2.7s;
		-ms-transition-delay: 2.7s;
		transition-delay: 2.7s;
	}

	.gallery.onscroll-fade-in article:nth-child(20) .image img {
		-moz-transition-delay: 2.85s;
		-webkit-transition-delay: 2.85s;
		-ms-transition-delay: 2.85s;
		transition-delay: 2.85s;
	}

	.gallery.onscroll-fade-in article:nth-child(21) .image img {
		-moz-transition-delay: 3s;
		-webkit-transition-delay: 3s;
		-ms-transition-delay: 3s;
		transition-delay: 3s;
	}

	.gallery.onscroll-fade-in article:nth-child(22) .image img {
		-moz-transition-delay: 3.15s;
		-webkit-transition-delay: 3.15s;
		-ms-transition-delay: 3.15s;
		transition-delay: 3.15s;
	}

	.gallery.onscroll-fade-in article:nth-child(23) .image img {
		-moz-transition-delay: 3.3s;
		-webkit-transition-delay: 3.3s;
		-ms-transition-delay: 3.3s;
		transition-delay: 3.3s;
	}

	.gallery.onscroll-fade-in article:nth-child(24) .image img {
		-moz-transition-delay: 3.45s;
		-webkit-transition-delay: 3.45s;
		-ms-transition-delay: 3.45s;
		transition-delay: 3.45s;
	}

	.gallery.onscroll-fade-in article:nth-child(25) .image img {
		-moz-transition-delay: 3.6s;
		-webkit-transition-delay: 3.6s;
		-ms-transition-delay: 3.6s;
		transition-delay: 3.6s;
	}

	.gallery.onscroll-fade-in article:nth-child(26) .image img {
		-moz-transition-delay: 3.75s;
		-webkit-transition-delay: 3.75s;
		-ms-transition-delay: 3.75s;
		transition-delay: 3.75s;
	}

	.gallery.onscroll-fade-in article:nth-child(27) .image img {
		-moz-transition-delay: 3.9s;
		-webkit-transition-delay: 3.9s;
		-ms-transition-delay: 3.9s;
		transition-delay: 3.9s;
	}

	.gallery.onscroll-fade-in article:nth-child(28) .image img {
		-moz-transition-delay: 4.05s;
		-webkit-transition-delay: 4.05s;
		-ms-transition-delay: 4.05s;
		transition-delay: 4.05s;
	}

	.gallery.onscroll-fade-in article:nth-child(29) .image img {
		-moz-transition-delay: 4.2s;
		-webkit-transition-delay: 4.2s;
		-ms-transition-delay: 4.2s;
		transition-delay: 4.2s;
	}

	.gallery.onscroll-fade-in article:nth-child(30) .image img {
		-moz-transition-delay: 4.35s;
		-webkit-transition-delay: 4.35s;
		-ms-transition-delay: 4.35s;
		transition-delay: 4.35s;
	}

	.gallery.onscroll-fade-in article:nth-child(31) .image img {
		-moz-transition-delay: 4.5s;
		-webkit-transition-delay: 4.5s;
		-ms-transition-delay: 4.5s;
		transition-delay: 4.5s;
	}

	.gallery.onscroll-fade-in article:nth-child(32) .image img {
		-moz-transition-delay: 4.65s;
		-webkit-transition-delay: 4.65s;
		-ms-transition-delay: 4.65s;
		transition-delay: 4.65s;
	}

	.gallery.onscroll-fade-in article:nth-child(33) .image img {
		-moz-transition-delay: 4.8s;
		-webkit-transition-delay: 4.8s;
		-ms-transition-delay: 4.8s;
		transition-delay: 4.8s;
	}

	.gallery.onscroll-fade-in.is-inactive article .image img {
		opacity: 0;
	}

/* Gallery (style1) */

	.gallery.style1 {
		background-color: #000000;
		color: #ffffff;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		position: relative;
		width: 100%;
		background-color: transparent;
	}

		.gallery.style1 input, .gallery.style1 select, .gallery.style1 textarea {
			color: #ffffff;
		}

		.gallery.style1 a {
			color: #ffffff;
		}

			.gallery.style1 a:hover {
				color: #47D3E5;
			}

		.gallery.style1 strong, .gallery.style1 b {
			color: #ffffff;
		}

		.gallery.style1 h1, .gallery.style1 h2, .gallery.style1 h3, .gallery.style1 h4, .gallery.style1 h5, .gallery.style1 h6 {
			color: #ffffff;
		}

		.gallery.style1 blockquote {
			border-left-color: white;
		}

		.gallery.style1 code {
			background: rgba(255, 255, 255, 0.125);
			border-color: white;
		}

		.gallery.style1 hr {
			border-bottom-color: white;
		}

		.gallery.style1 input[type="submit"],
		.gallery.style1 input[type="reset"],
		.gallery.style1 input[type="button"],
		.gallery.style1 button,
		.gallery.style1 .button {
			background-color: transparent;
			box-shadow: inset 0 0 0 1px white;
			color: #ffffff !important;
		}

			.gallery.style1 input[type="submit"]:hover,
			.gallery.style1 input[type="reset"]:hover,
			.gallery.style1 input[type="button"]:hover,
			.gallery.style1 button:hover,
			.gallery.style1 .button:hover {
				box-shadow: inset 0 0 0 1px #47D3E5;
				color: #47D3E5 !important;
			}

			.gallery.style1 input[type="submit"]:active,
			.gallery.style1 input[type="reset"]:active,
			.gallery.style1 input[type="button"]:active,
			.gallery.style1 button:active,
			.gallery.style1 .button:active {
				background-color: rgba(71, 211, 229, 0.2);
				box-shadow: inset 0 0 0 1px #47D3E5;
				color: #47D3E5 !important;
			}

			.gallery.style1 input[type="submit"].primary,
			.gallery.style1 input[type="reset"].primary,
			.gallery.style1 input[type="button"].primary,
			.gallery.style1 button.primary,
			.gallery.style1 .button.primary {
				background-color: #ffffff;
				box-shadow: none;
				color: #000000 !important;
			}

				.gallery.style1 input[type="submit"].primary:hover,
				.gallery.style1 input[type="reset"].primary:hover,
				.gallery.style1 input[type="button"].primary:hover,
				.gallery.style1 button.primary:hover,
				.gallery.style1 .button.primary:hover {
					background-color: #47D3E5;
				}

				.gallery.style1 input[type="submit"].primary:active,
				.gallery.style1 input[type="reset"].primary:active,
				.gallery.style1 input[type="button"].primary:active,
				.gallery.style1 button.primary:active,
				.gallery.style1 .button.primary:active {
					background-color: #1ebdd1;
				}

		.gallery.style1 > .forward, .gallery.style1 > .backward {
			display: none;
		}

		.gallery.style1 > .inner {
			-moz-align-items: inherit;
			-webkit-align-items: inherit;
			-ms-align-items: inherit;
			align-items: inherit;
			display: inherit;
			-moz-flex-wrap: inherit;
			-webkit-flex-wrap: inherit;
			-ms-flex-wrap: inherit;
			flex-wrap: inherit;
			-moz-justify-content: inherit;
			-webkit-justify-content: inherit;
			-ms-justify-content: inherit;
			justify-content: inherit;
		}

		.gallery.style1 article {
			overflow: hidden;
			position: relative;
			width: 25%;
		}

			.gallery.style1 article .image {
				-moz-transition: opacity 0.2s ease-in-out;
				-webkit-transition: opacity 0.2s ease-in-out;
				-ms-transition: opacity 0.2s ease-in-out;
				transition: opacity 0.2s ease-in-out;
				display: block;
				width: 100%;
				border-radius: 0;
			}

				.gallery.style1 article .image img {
					display: block;
					width: 100%;
					border-radius: 0;
				}

			.gallery.style1 article .caption {
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				display: -moz-flex;
				display: -webkit-flex;
				display: -ms-flex;
				display: flex;
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				-moz-justify-content: center;
				-webkit-justify-content: center;
				-ms-justify-content: center;
				justify-content: center;
				pointer-events: none;
				-moz-transition: opacity 0.2s ease-in-out;
				-webkit-transition: opacity 0.2s ease-in-out;
				-ms-transition: opacity 0.2s ease-in-out;
				transition: opacity 0.2s ease-in-out;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				background-color: rgba(0, 0, 0, 0.5);
				opacity: 0;
				padding: 2rem;
				z-index: 1;
				font-size: 0.8rem;
			}

				.gallery.style1 article .caption a {
					pointer-events: auto;
				}

				.gallery.style1 article .caption h2, .gallery.style1 article .caption h3, .gallery.style1 article .caption h4, .gallery.style1 article .caption h5, .gallery.style1 article .caption h6 {
					font-size: 1.25rem;
					margin-bottom: 0.25rem;
				}

				.gallery.style1 article .caption > * {
					max-width: 100%;
					margin-bottom: 1rem;
				}

				.gallery.style1 article .caption > :last-child {
					margin-bottom: 0;
				}

			.gallery.style1 article:hover .caption {
				opacity: 1;
			}

		@media screen and (max-width: 1280px) {

			.gallery.style1 article {
				width: 33.33333%;
			}

				.gallery.style1 article .caption {
					padding: 1rem;
				}

		}

		@media screen and (max-width: 980px) {

			.gallery.style1 article {
				width: 50%;
			}

				.gallery.style1 article .caption {
					padding: 1rem;
				}

		}

		@media screen and (max-width: 480px) {

			.gallery.style1 article {
				width: 100%;
			}

				.gallery.style1 article .caption {
					padding: 1rem;
				}

		}

		.gallery.style1.small article {
			width: 20%;
		}

			.gallery.style1.small article .caption {
				padding: 1rem;
			}

		@media screen and (max-width: 1280px) {

			.gallery.style1.small article {
				width: 25%;
			}

				.gallery.style1.small article .caption {
					padding: 1rem;
				}

		}

		@media screen and (max-width: 980px) {

			.gallery.style1.small article {
				width: 33.33333%;
			}

				.gallery.style1.small article .caption {
					padding: 1rem;
				}

		}

		@media screen and (max-width: 480px) {

			.gallery.style1.small article {
				width: 50%;
			}

				.gallery.style1.small article .caption {
					padding: 1rem;
				}

		}

		.gallery.style1.big article {
			width: 33.33333%;
		}

			.gallery.style1.big article .caption {
				padding: 3rem;
			}

		@media screen and (max-width: 1280px) {

			.gallery.style1.big article {
				width: 50%;
			}

				.gallery.style1.big article .caption {
					padding: 2rem;
				}

		}

		@media screen and (max-width: 980px) {

			.gallery.style1.big article {
				width: 50%;
			}

				.gallery.style1.big article .caption {
					padding: 2rem;
				}

		}

		@media screen and (max-width: 480px) {

			.gallery.style1.big article {
				width: 100%;
			}

				.gallery.style1.big article .caption {
					padding: 1rem;
				}

		}

/* Gallery (style2) */

	.gallery.style2 {
		background-color: #000000;
		color: #ffffff;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-webkit-overflow-scrolling: touch;
		position: relative;
		background-color: transparent;
	}

		.gallery.style2 input, .gallery.style2 select, .gallery.style2 textarea {
			color: #ffffff;
		}

		.gallery.style2 a {
			color: #ffffff;
		}

			.gallery.style2 a:hover {
				color: #47D3E5;
			}

		.gallery.style2 strong, .gallery.style2 b {
			color: #ffffff;
		}

		.gallery.style2 h1, .gallery.style2 h2, .gallery.style2 h3, .gallery.style2 h4, .gallery.style2 h5, .gallery.style2 h6 {
			color: #ffffff;
		}

		.gallery.style2 blockquote {
			border-left-color: white;
		}

		.gallery.style2 code {
			background: rgba(255, 255, 255, 0.125);
			border-color: white;
		}

		.gallery.style2 hr {
			border-bottom-color: white;
		}

		.gallery.style2 input[type="submit"],
		.gallery.style2 input[type="reset"],
		.gallery.style2 input[type="button"],
		.gallery.style2 button,
		.gallery.style2 .button {
			background-color: transparent;
			box-shadow: inset 0 0 0 1px white;
			color: #ffffff !important;
		}

			.gallery.style2 input[type="submit"]:hover,
			.gallery.style2 input[type="reset"]:hover,
			.gallery.style2 input[type="button"]:hover,
			.gallery.style2 button:hover,
			.gallery.style2 .button:hover {
				box-shadow: inset 0 0 0 1px #47D3E5;
				color: #47D3E5 !important;
			}

			.gallery.style2 input[type="submit"]:active,
			.gallery.style2 input[type="reset"]:active,
			.gallery.style2 input[type="button"]:active,
			.gallery.style2 button:active,
			.gallery.style2 .button:active {
				background-color: rgba(71, 211, 229, 0.2);
				box-shadow: inset 0 0 0 1px #47D3E5;
				color: #47D3E5 !important;
			}

			.gallery.style2 input[type="submit"].primary,
			.gallery.style2 input[type="reset"].primary,
			.gallery.style2 input[type="button"].primary,
			.gallery.style2 button.primary,
			.gallery.style2 .button.primary {
				background-color: #ffffff;
				box-shadow: none;
				color: #000000 !important;
			}

				.gallery.style2 input[type="submit"].primary:hover,
				.gallery.style2 input[type="reset"].primary:hover,
				.gallery.style2 input[type="button"].primary:hover,
				.gallery.style2 button.primary:hover,
				.gallery.style2 .button.primary:hover {
					background-color: #47D3E5;
				}

				.gallery.style2 input[type="submit"].primary:active,
				.gallery.style2 input[type="reset"].primary:active,
				.gallery.style2 input[type="button"].primary:active,
				.gallery.style2 button.primary:active,
				.gallery.style2 .button.primary:active {
					background-color: #1ebdd1;
				}

		.gallery.style2 > .forward, .gallery.style2 > .backward {
			text-decoration: none;
			-moz-transition: opacity 0.2s ease-in-out;
			-webkit-transition: opacity 0.2s ease-in-out;
			-ms-transition: opacity 0.2s ease-in-out;
			transition: opacity 0.2s ease-in-out;
			position: absolute;
			top: 0;
			width: 5rem;
			height: 100%;
			cursor: pointer;
			opacity: 0;
			z-index: 2;
		}

			.gallery.style2 > .forward:before, .gallery.style2 > .backward:before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				display: inline-block;
				font-style: normal;
				font-variant: normal;
				text-rendering: auto;
				line-height: 1;
				text-transform: none !important;
				font-family: 'Font Awesome 5 Free';
				font-weight: 900;
			}

			.gallery.style2 > .forward:before, .gallery.style2 > .backward:before {
				display: block;
				top: calc(50% - 1.5rem);
				width: 4rem;
				height: 3rem;
				line-height: 1em;
				font-size: 3rem;
				position: absolute;
				text-align: center;
			}

		.gallery.style2:hover > .forward, .gallery.style2:hover > .backward {
			opacity: 1;
		}

		.gallery.style2 > .forward {
			right: 0;
			background-image: linear-gradient(to left, rgba(0, 0, 0, 0.25) 15%, rgba(0, 0, 0, 0));
		}

			.gallery.style2 > .forward:before {
				content: '\f105';
				right: 0;
			}

		.gallery.style2 > .backward {
			left: 0;
			background-image: linear-gradient(to right, rgba(0, 0, 0, 0.25) 15%, rgba(0, 0, 0, 0));
		}

			.gallery.style2 > .backward:before {
				content: '\f104';
				left: 0;
			}

		.gallery.style2 > .inner {
			display: inherit;
			overflow-x: auto;
			overflow-y: hidden;
			position: relative;
			width: 100%;
		}

		.gallery.style2 article {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			display: block;
			position: relative;
			overflow: hidden;
			width: 22.5rem;
			max-width: 75vw;
		}

			.gallery.style2 article .image {
				display: block;
				width: 100%;
				border-radius: 0;
			}

				.gallery.style2 article .image img {
					display: block;
					width: 100%;
					border-radius: 0;
				}

			.gallery.style2 article .caption {
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				display: -moz-flex;
				display: -webkit-flex;
				display: -ms-flex;
				display: flex;
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				-moz-justify-content: center;
				-webkit-justify-content: center;
				-ms-justify-content: center;
				justify-content: center;
				pointer-events: none;
				-moz-transition: opacity 0.2s ease-in-out;
				-webkit-transition: opacity 0.2s ease-in-out;
				-ms-transition: opacity 0.2s ease-in-out;
				transition: opacity 0.2s ease-in-out;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				background-color: rgba(0, 0, 0, 0.5);
				opacity: 0;
				padding: 3rem;
				z-index: 1;
				font-size: 0.8rem;
			}

				.gallery.style2 article .caption a {
					pointer-events: auto;
				}

				.gallery.style2 article .caption h2, .gallery.style2 article .caption h3, .gallery.style2 article .caption h4, .gallery.style2 article .caption h5, .gallery.style2 article .caption h6 {
					font-size: 1.25rem;
					margin-bottom: 0.25rem;
				}

				.gallery.style2 article .caption > * {
					max-width: 100%;
					margin-bottom: 1rem;
				}

				.gallery.style2 article .caption > :last-child {
					margin-bottom: 0;
				}

			.gallery.style2 article:hover .caption {
				opacity: 1;
			}

		@media screen and (max-width: 980px) {

			.gallery.style2 article .caption {
				padding: 2rem;
			}

		}

		@media screen and (max-width: 736px) {

			.gallery.style2 article .caption {
				padding: 2rem;
			}

		}

		.gallery.style2.small article {
			width: 17.5rem;
		}

			.gallery.style2.small article .caption {
				padding: 2rem;
			}

		@media screen and (max-width: 980px) {

			.gallery.style2.small article .caption {
				padding: 2rem;
			}

		}

		@media screen and (max-width: 736px) {

			.gallery.style2.small article .caption {
				padding: 2rem;
			}

		}

		.gallery.style2.big article {
			width: 30rem;
		}

			.gallery.style2.big article .caption {
				padding: 4rem;
			}

		@media screen and (max-width: 980px) {

			.gallery.style2.big article .caption {
				padding: 3rem;
			}

		}

		@media screen and (max-width: 736px) {

			.gallery.style2.big article .caption {
				padding: 2rem;
			}

		}

/* Gallery (lightbox) */

	@-moz-keyframes gallery-modal-spinner {
		0% {
			-moz-transform: rotate(0deg);
			-webkit-transform: rotate(0deg);
			-ms-transform: rotate(0deg);
			transform: rotate(0deg);
		}

		100% {
			-moz-transform: rotate(360deg);
			-webkit-transform: rotate(360deg);
			-ms-transform: rotate(360deg);
			transform: rotate(360deg);
		}
	}

	@-webkit-keyframes gallery-modal-spinner {
		0% {
			-moz-transform: rotate(0deg);
			-webkit-transform: rotate(0deg);
			-ms-transform: rotate(0deg);
			transform: rotate(0deg);
		}

		100% {
			-moz-transform: rotate(360deg);
			-webkit-transform: rotate(360deg);
			-ms-transform: rotate(360deg);
			transform: rotate(360deg);
		}
	}

	@-ms-keyframes gallery-modal-spinner {
		0% {
			-moz-transform: rotate(0deg);
			-webkit-transform: rotate(0deg);
			-ms-transform: rotate(0deg);
			transform: rotate(0deg);
		}

		100% {
			-moz-transform: rotate(360deg);
			-webkit-transform: rotate(360deg);
			-ms-transform: rotate(360deg);
			transform: rotate(360deg);
		}
	}

	@keyframes gallery-modal-spinner {
		0% {
			-moz-transform: rotate(0deg);
			-webkit-transform: rotate(0deg);
			-ms-transform: rotate(0deg);
			transform: rotate(0deg);
		}

		100% {
			-moz-transform: rotate(360deg);
			-webkit-transform: rotate(360deg);
			-ms-transform: rotate(360deg);
			transform: rotate(360deg);
		}
	}

	.gallery.lightbox .modal {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		pointer-events: none;
		-moz-user-select: none;
		-webkit-user-select: none;
		-ms-user-select: none;
		user-select: none;
		-moz-transition: opacity 0.5s ease, visibility 0.5s, z-index 0.5s;
		-webkit-transition: opacity 0.5s ease, visibility 0.5s, z-index 0.5s;
		-ms-transition: opacity 0.5s ease, visibility 0.5s, z-index 0.5s;
		transition: opacity 0.5s ease, visibility 0.5s, z-index 0.5s;
		-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		outline: 0;
		background-color: rgba(0, 0, 0, 0.75);
		visibility: none;
		opacity: 0;
		z-index: 0;
	}

		.gallery.lightbox .modal:before {
			-moz-animation: gallery-modal-spinner 1s infinite linear;
			-webkit-animation: gallery-modal-spinner 1s infinite linear;
			-ms-animation: gallery-modal-spinner 1s infinite linear;
			animation: gallery-modal-spinner 1s infinite linear;
			-moz-transition: opacity 0.25s ease;
			-webkit-transition: opacity 0.25s ease;
			-ms-transition: opacity 0.25s ease;
			transition: opacity 0.25s ease;
			-moz-transition-delay: 0.5s;
			-webkit-transition-delay: 0.5s;
			-ms-transition-delay: 0.5s;
			transition-delay: 0.5s;
			content: '';
			display: block;
			position: absolute;
			top: 50%;
			left: 50%;
			width: 4rem;
			height: 4rem;
			margin: -2rem 0 0 -2rem;
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='96px' height='96px' viewBox='0 0 96 96' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: %23ffffff%3B stroke-width: 1.5px%3B %7D%3C/style%3E%3Cdefs%3E%3CclipPath id='corner'%3E%3Cpolygon points='0,0 48,0 48,48 96,48 96,96 0,96' /%3E%3C/clipPath%3E%3C/defs%3E%3Cg clip-path='url(%23corner)'%3E%3Ccircle cx='48' cy='48' r='32'/%3E%3C/g%3E%3C/svg%3E");
			background-position: center;
			background-repeat: no-repeat;
			background-size: 4rem;
			opacity: 0;
		}

		.gallery.lightbox .modal:after {
			content: '';
			display: block;
			position: absolute;
			top: 0.5rem;
			right: 0.5rem;
			width: 4rem;
			height: 4rem;
			cursor: pointer;
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='64px' viewBox='0 0 64 64' zoomAndPan='disable'%3E%3Cstyle%3Eline %7Bstroke: %23ffffff%3Bstroke-width: 1.5px%3B%7D%3C/style%3E%3Cline x1='20' y1='20' x2='44' y2='44' /%3E%3Cline x1='20' y1='44' x2='44' y2='20' /%3E%3C/svg%3E");
			background-position: center;
			background-repeat: no-repeat;
			background-size: 3rem;
		}

		.gallery.lightbox .modal .inner {
			-moz-transform: translateY(0.75rem);
			-webkit-transform: translateY(0.75rem);
			-ms-transform: translateY(0.75rem);
			transform: translateY(0.75rem);
			-moz-transition: opacity 0.25s ease, -moz-transform 0.25s ease;
			-webkit-transition: opacity 0.25s ease, -webkit-transform 0.25s ease;
			-ms-transition: opacity 0.25s ease, -ms-transform 0.25s ease;
			transition: opacity 0.25s ease, transform 0.25s ease;
			opacity: 0;
		}

			.gallery.lightbox .modal .inner img {
				display: block;
				max-width: 90vw;
				max-height: 85vh;
				box-shadow: 0 1rem 3rem 0 rgba(0, 0, 0, 0.35);
			}

		.gallery.lightbox .modal.visible {
			pointer-events: auto;
			visibility: visible;
			opacity: 1;
			z-index: 10001;
		}

			.gallery.lightbox .modal.visible:before {
				opacity: 1;
			}

		.gallery.lightbox .modal.loaded .inner {
			-moz-transform: translateY(0);
			-webkit-transform: translateY(0);
			-ms-transform: translateY(0);
			transform: translateY(0);
			-moz-transition: opacity 0.5s ease, -moz-transform 0.5s ease;
			-webkit-transition: opacity 0.5s ease, -webkit-transform 0.5s ease;
			-ms-transition: opacity 0.5s ease, -ms-transform 0.5s ease;
			transition: opacity 0.5s ease, transform 0.5s ease;
			opacity: 1;
		}

		.gallery.lightbox .modal.loaded:before {
			-moz-transition-delay: 0s;
			-webkit-transition-delay: 0s;
			-ms-transition-delay: 0s;
			transition-delay: 0s;
			opacity: 0;
		}

	@media screen and (max-width: 980px) {

		.gallery.lightbox .modal .inner img {
			max-width: 100vw;
		}

	}

	.gallery article .image {
		background-color: rgba(0, 0, 0, 0.125);
	}

/* Wrapper (style1) */

	.wrapper.style1 > .inner {
		padding: 7rem 3.5rem 5rem 3.5rem ;
		margin: 0 auto;
		max-width: 100%;
		width: 64rem;
	}

		.wrapper.style1 > .inner.medium {
			width: 48rem;
		}

		.wrapper.style1 > .inner.small {
			width: 32rem;
		}

	@media screen and (max-width: 1680px) {

		.wrapper.style1 > .inner {
			padding: 5rem 2.5rem 3rem 2.5rem ;
		}

	}

	@media screen and (max-width: 1280px) {

		.wrapper.style1 > .inner {
			padding: 4rem 4rem 2rem 4rem ;
		}

	}

	@media screen and (max-width: 980px) {

		.wrapper.style1 > .inner {
			padding: 4.5rem 3rem 2.5rem 3rem ;
		}

	}

	@media screen and (max-width: 736px) {

		.wrapper.style1 > .inner {
			padding: 3rem 2rem 1rem 2rem ;
		}

	}

/* Wrapper (style2) */

	.wrapper.style2 {
		padding: 7rem;
		background-color: #eeeeee;
	}

		.wrapper.style2 > .inner {
			padding: 5.25rem 3.5rem 3.25rem 3.5rem ;
			background-color: #ffffff;
			border-radius: 0.5rem;
			margin: 0 auto;
			max-width: 100%;
			position: relative;
			width: 64rem;
			z-index: 1;
		}

			.wrapper.style2 > .inner.medium {
				width: 48rem;
			}

			.wrapper.style2 > .inner.small {
				width: 32rem;
			}

		@media screen and (max-width: 1680px) {

			.wrapper.style2 {
				padding: 5rem;
			}

				.wrapper.style2 > .inner {
					padding: 3.75rem 2.5rem 1.75rem 2.5rem ;
				}

		}

		@media screen and (max-width: 1280px) {

			.wrapper.style2 {
				padding: 4rem;
			}

				.wrapper.style2 > .inner {
					padding: 3rem 2rem 1rem 2rem ;
				}

		}

		@media screen and (max-width: 980px) {

			.wrapper.style2 {
				padding: 2.25rem;
			}

				.wrapper.style2 > .inner {
					padding: 3rem 2.25rem 1rem 2.25rem ;
				}

		}

		@media screen and (max-width: 736px) {

			.wrapper.style2 {
				padding: 1.5rem;
			}

				.wrapper.style2 > .inner {
					padding: 2rem 1.5rem 0.1rem 1.5rem ;
				}

		}

	#wrapper > .wrapper.style2.invert:not(.color1):not(.color2):not(.color3):not(.color4):not(.color5):not(.color6):not(.color7) {
		background-color: #222222;
	}

	#wrapper > .wrapper.style2.invert > .inner {
		background-color: #000000;
	}

/* Items (transitions) */

	.items.onload-fade-in > * > .inner {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
		-moz-transition-delay: 2.4s;
		-webkit-transition-delay: 2.4s;
		-ms-transition-delay: 2.4s;
		transition-delay: 2.4s;
	}

	.items.onload-fade-in > *:nth-child(1) > .inner {
		-moz-transition-delay: 0s;
		-webkit-transition-delay: 0s;
		-ms-transition-delay: 0s;
		transition-delay: 0s;
	}

	.items.onload-fade-in > *:nth-child(2) > .inner {
		-moz-transition-delay: 0.15s;
		-webkit-transition-delay: 0.15s;
		-ms-transition-delay: 0.15s;
		transition-delay: 0.15s;
	}

	.items.onload-fade-in > *:nth-child(3) > .inner {
		-moz-transition-delay: 0.3s;
		-webkit-transition-delay: 0.3s;
		-ms-transition-delay: 0.3s;
		transition-delay: 0.3s;
	}

	.items.onload-fade-in > *:nth-child(4) > .inner {
		-moz-transition-delay: 0.45s;
		-webkit-transition-delay: 0.45s;
		-ms-transition-delay: 0.45s;
		transition-delay: 0.45s;
	}

	.items.onload-fade-in > *:nth-child(5) > .inner {
		-moz-transition-delay: 0.6s;
		-webkit-transition-delay: 0.6s;
		-ms-transition-delay: 0.6s;
		transition-delay: 0.6s;
	}

	.items.onload-fade-in > *:nth-child(6) > .inner {
		-moz-transition-delay: 0.75s;
		-webkit-transition-delay: 0.75s;
		-ms-transition-delay: 0.75s;
		transition-delay: 0.75s;
	}

	.items.onload-fade-in > *:nth-child(7) > .inner {
		-moz-transition-delay: 0.9s;
		-webkit-transition-delay: 0.9s;
		-ms-transition-delay: 0.9s;
		transition-delay: 0.9s;
	}

	.items.onload-fade-in > *:nth-child(8) > .inner {
		-moz-transition-delay: 1.05s;
		-webkit-transition-delay: 1.05s;
		-ms-transition-delay: 1.05s;
		transition-delay: 1.05s;
	}

	.items.onload-fade-in > *:nth-child(9) > .inner {
		-moz-transition-delay: 1.2s;
		-webkit-transition-delay: 1.2s;
		-ms-transition-delay: 1.2s;
		transition-delay: 1.2s;
	}

	.items.onload-fade-in > *:nth-child(10) > .inner {
		-moz-transition-delay: 1.35s;
		-webkit-transition-delay: 1.35s;
		-ms-transition-delay: 1.35s;
		transition-delay: 1.35s;
	}

	.items.onload-fade-in > *:nth-child(11) > .inner {
		-moz-transition-delay: 1.5s;
		-webkit-transition-delay: 1.5s;
		-ms-transition-delay: 1.5s;
		transition-delay: 1.5s;
	}

	.items.onload-fade-in > *:nth-child(12) > .inner {
		-moz-transition-delay: 1.65s;
		-webkit-transition-delay: 1.65s;
		-ms-transition-delay: 1.65s;
		transition-delay: 1.65s;
	}

	.items.onload-fade-in > *:nth-child(13) > .inner {
		-moz-transition-delay: 1.8s;
		-webkit-transition-delay: 1.8s;
		-ms-transition-delay: 1.8s;
		transition-delay: 1.8s;
	}

	.items.onload-fade-in > *:nth-child(14) > .inner {
		-moz-transition-delay: 1.95s;
		-webkit-transition-delay: 1.95s;
		-ms-transition-delay: 1.95s;
		transition-delay: 1.95s;
	}

	.items.onload-fade-in > *:nth-child(15) > .inner {
		-moz-transition-delay: 2.1s;
		-webkit-transition-delay: 2.1s;
		-ms-transition-delay: 2.1s;
		transition-delay: 2.1s;
	}

	.items.onload-fade-in > *:nth-child(16) > .inner {
		-moz-transition-delay: 2.25s;
		-webkit-transition-delay: 2.25s;
		-ms-transition-delay: 2.25s;
		transition-delay: 2.25s;
	}

	.items.onload-fade-in > *:nth-child(17) > .inner {
		-moz-transition-delay: 2.4s;
		-webkit-transition-delay: 2.4s;
		-ms-transition-delay: 2.4s;
		transition-delay: 2.4s;
	}

	body.is-preload .items.onload-fade-in > * > .inner {
		opacity: 0;
	}

	.items.onscroll-fade-in > * > .inner {
		-moz-transition: opacity 0.75s ease-in-out;
		-webkit-transition: opacity 0.75s ease-in-out;
		-ms-transition: opacity 0.75s ease-in-out;
		transition: opacity 0.75s ease-in-out;
		-moz-transition-delay: 2.4s;
		-webkit-transition-delay: 2.4s;
		-ms-transition-delay: 2.4s;
		transition-delay: 2.4s;
	}

	.items.onscroll-fade-in > *:nth-child(1) > .inner {
		-moz-transition-delay: 0s;
		-webkit-transition-delay: 0s;
		-ms-transition-delay: 0s;
		transition-delay: 0s;
	}

	.items.onscroll-fade-in > *:nth-child(2) > .inner {
		-moz-transition-delay: 0.15s;
		-webkit-transition-delay: 0.15s;
		-ms-transition-delay: 0.15s;
		transition-delay: 0.15s;
	}

	.items.onscroll-fade-in > *:nth-child(3) > .inner {
		-moz-transition-delay: 0.3s;
		-webkit-transition-delay: 0.3s;
		-ms-transition-delay: 0.3s;
		transition-delay: 0.3s;
	}

	.items.onscroll-fade-in > *:nth-child(4) > .inner {
		-moz-transition-delay: 0.45s;
		-webkit-transition-delay: 0.45s;
		-ms-transition-delay: 0.45s;
		transition-delay: 0.45s;
	}

	.items.onscroll-fade-in > *:nth-child(5) > .inner {
		-moz-transition-delay: 0.6s;
		-webkit-transition-delay: 0.6s;
		-ms-transition-delay: 0.6s;
		transition-delay: 0.6s;
	}

	.items.onscroll-fade-in > *:nth-child(6) > .inner {
		-moz-transition-delay: 0.75s;
		-webkit-transition-delay: 0.75s;
		-ms-transition-delay: 0.75s;
		transition-delay: 0.75s;
	}

	.items.onscroll-fade-in > *:nth-child(7) > .inner {
		-moz-transition-delay: 0.9s;
		-webkit-transition-delay: 0.9s;
		-ms-transition-delay: 0.9s;
		transition-delay: 0.9s;
	}

	.items.onscroll-fade-in > *:nth-child(8) > .inner {
		-moz-transition-delay: 1.05s;
		-webkit-transition-delay: 1.05s;
		-ms-transition-delay: 1.05s;
		transition-delay: 1.05s;
	}

	.items.onscroll-fade-in > *:nth-child(9) > .inner {
		-moz-transition-delay: 1.2s;
		-webkit-transition-delay: 1.2s;
		-ms-transition-delay: 1.2s;
		transition-delay: 1.2s;
	}

	.items.onscroll-fade-in > *:nth-child(10) > .inner {
		-moz-transition-delay: 1.35s;
		-webkit-transition-delay: 1.35s;
		-ms-transition-delay: 1.35s;
		transition-delay: 1.35s;
	}

	.items.onscroll-fade-in > *:nth-child(11) > .inner {
		-moz-transition-delay: 1.5s;
		-webkit-transition-delay: 1.5s;
		-ms-transition-delay: 1.5s;
		transition-delay: 1.5s;
	}

	.items.onscroll-fade-in > *:nth-child(12) > .inner {
		-moz-transition-delay: 1.65s;
		-webkit-transition-delay: 1.65s;
		-ms-transition-delay: 1.65s;
		transition-delay: 1.65s;
	}

	.items.onscroll-fade-in > *:nth-child(13) > .inner {
		-moz-transition-delay: 1.8s;
		-webkit-transition-delay: 1.8s;
		-ms-transition-delay: 1.8s;
		transition-delay: 1.8s;
	}

	.items.onscroll-fade-in > *:nth-child(14) > .inner {
		-moz-transition-delay: 1.95s;
		-webkit-transition-delay: 1.95s;
		-ms-transition-delay: 1.95s;
		transition-delay: 1.95s;
	}

	.items.onscroll-fade-in > *:nth-child(15) > .inner {
		-moz-transition-delay: 2.1s;
		-webkit-transition-delay: 2.1s;
		-ms-transition-delay: 2.1s;
		transition-delay: 2.1s;
	}

	.items.onscroll-fade-in > *:nth-child(16) > .inner {
		-moz-transition-delay: 2.25s;
		-webkit-transition-delay: 2.25s;
		-ms-transition-delay: 2.25s;
		transition-delay: 2.25s;
	}

	.items.onscroll-fade-in > *:nth-child(17) > .inner {
		-moz-transition-delay: 2.4s;
		-webkit-transition-delay: 2.4s;
		-ms-transition-delay: 2.4s;
		transition-delay: 2.4s;
	}

	.items.onscroll-fade-in.is-inactive > * > .inner {
		opacity: 0;
	}

/* Items (style1) */

	.items.style1 {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		margin: 3rem 0;
		position: relative;
	}

		.items.style1 > * {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			border-style: solid;
			border-left-width: 1px;
			border-top-width: 1px;
		}

		.items.style1.big > * {
			padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
			width: 50%;
		}

			.items.style1.big > *:nth-child(-n + 2) {
				border-top-width: 0;
			}

			.items.style1.big > *:nth-child(2n + 1) {
				border-left-width: 0;
			}

		.items.style1.medium > * {
			padding: 2.1875rem 2.1875rem 0.1875rem 2.1875rem ;
			width: 33.33333%;
		}

			.items.style1.medium > *:nth-child(-n + 3) {
				border-top-width: 0;
			}

			.items.style1.medium > *:nth-child(3n + 1) {
				border-left-width: 0;
			}

		.items.style1.small > * {
			padding: 1.3125rem 1.3125rem 0.1rem 1.3125rem ;
			width: 25%;
		}

			.items.style1.small > *:nth-child(-n + 4) {
				border-top-width: 0;
			}

			.items.style1.small > *:nth-child(4n + 1) {
				border-left-width: 0;
			}

		@media screen and (max-width: 1280px) {

			.items.style1.small > *:nth-child(-n + 4) {
				border-top-width: 1px;
			}

			.items.style1.small > *:nth-child(4n + 1) {
				border-left-width: 1px;
			}

			.items.style1.small > * {
				padding: 2.1875rem 2.1875rem 0.1875rem 2.1875rem ;
				width: 33.33333%;
			}

				.items.style1.small > *:nth-child(-n + 3) {
					border-top-width: 0;
				}

				.items.style1.small > *:nth-child(3n + 1) {
					border-left-width: 0;
				}

		}

		@media screen and (max-width: 980px) {

			.items.style1.medium > *:nth-child(-n + 3) {
				border-top-width: 1px;
			}

			.items.style1.medium > *:nth-child(3n + 1) {
				border-left-width: 1px;
			}

			.items.style1.medium > * {
				padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
				width: 50%;
			}

				.items.style1.medium > *:nth-child(-n + 2) {
					border-top-width: 0;
				}

				.items.style1.medium > *:nth-child(2n + 1) {
					border-left-width: 0;
				}

			.items.style1.small > *:nth-child(-n + 3) {
				border-top-width: 1px;
			}

			.items.style1.small > *:nth-child(3n + 1) {
				border-left-width: 1px;
			}

			.items.style1.small > * {
				padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
				width: 50%;
			}

				.items.style1.small > *:nth-child(-n + 2) {
					border-top-width: 0;
				}

				.items.style1.small > *:nth-child(2n + 1) {
					border-left-width: 0;
				}

		}

		@media screen and (max-width: 480px) {

			.items.style1.big > *:nth-child(-n + 2) {
				border-top-width: 1px;
			}

			.items.style1.big > *:nth-child(2n + 1) {
				border-left-width: 1px;
			}

			.items.style1.big > * {
				padding: 2.625rem 2.625rem 0.625rem 2.625rem ;
				width: 100%;
			}

				.items.style1.big > *:nth-child(-n + 1) {
					border-top-width: 0;
				}

				.items.style1.big > *:nth-child(1n + 1) {
					border-left-width: 0;
				}

			.items.style1.medium > *:nth-child(-n + 2) {
				border-top-width: 1px;
			}

			.items.style1.medium > *:nth-child(2n + 1) {
				border-left-width: 1px;
			}

			.items.style1.medium > * {
				padding: 2.625rem 2.625rem 0.625rem 2.625rem ;
				width: 100%;
			}

				.items.style1.medium > *:nth-child(-n + 1) {
					border-top-width: 0;
				}

				.items.style1.medium > *:nth-child(1n + 1) {
					border-left-width: 0;
				}

			.items.style1.small > *:nth-child(-n + 2) {
				border-top-width: 1px;
			}

			.items.style1.small > *:nth-child(2n + 1) {
				border-left-width: 1px;
			}

			.items.style1.small > * {
				padding: 2.625rem 2.625rem 0.625rem 2.625rem ;
				width: 100%;
			}

				.items.style1.small > *:nth-child(-n + 1) {
					border-top-width: 0;
				}

				.items.style1.small > *:nth-child(1n + 1) {
					border-left-width: 0;
				}

			.items.style1.big > *, .items.style1.medium > *, .items.style1.small > * {
				padding-left: 0;
				padding-right: 0;
			}

			.items.style1.big > :first-child, .items.style1.medium > :first-child, .items.style1.small > :first-child {
				padding-top: 0;
			}

			.items.style1.big > :last-child, .items.style1.medium > :last-child, .items.style1.small > :last-child {
				padding-bottom: 0;
			}

				.items.style1.big > :last-child > .inner > :last-child, .items.style1.medium > :last-child > .inner > :last-child, .items.style1.small > :last-child > .inner > :last-child {
					margin-bottom: 0;
				}

		}

/* Items (style2) */

	.items.style2 {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		margin: 3rem 0;
		position: relative;
		border: solid 1px;
		border-radius: 4px;
	}

		.items.style2 > * {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			border-style: solid;
			border-left-width: 1px;
			border-top-width: 1px;
		}

		.items.style2.big > * {
			padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
			width: 50%;
		}

			.items.style2.big > *:nth-child(-n + 2) {
				border-top-width: 0;
			}

			.items.style2.big > *:nth-child(2n + 1) {
				border-left-width: 0;
			}

		.items.style2.medium > * {
			padding: 2.1875rem 2.1875rem 0.1875rem 2.1875rem ;
			width: 33.33333%;
		}

			.items.style2.medium > *:nth-child(-n + 3) {
				border-top-width: 0;
			}

			.items.style2.medium > *:nth-child(3n + 1) {
				border-left-width: 0;
			}

		.items.style2.small > * {
			padding: 1.3125rem 1.3125rem 0.1rem 1.3125rem ;
			width: 25%;
		}

			.items.style2.small > *:nth-child(-n + 4) {
				border-top-width: 0;
			}

			.items.style2.small > *:nth-child(4n + 1) {
				border-left-width: 0;
			}

		@media screen and (max-width: 1280px) {

			.items.style2.small > *:nth-child(-n + 4) {
				border-top-width: 1px;
			}

			.items.style2.small > *:nth-child(4n + 1) {
				border-left-width: 1px;
			}

			.items.style2.small > * {
				padding: 2.1875rem 2.1875rem 0.1875rem 2.1875rem ;
				width: 33.33333%;
			}

				.items.style2.small > *:nth-child(-n + 3) {
					border-top-width: 0;
				}

				.items.style2.small > *:nth-child(3n + 1) {
					border-left-width: 0;
				}

		}

		@media screen and (max-width: 980px) {

			.items.style2.medium > *:nth-child(-n + 3) {
				border-top-width: 1px;
			}

			.items.style2.medium > *:nth-child(3n + 1) {
				border-left-width: 1px;
			}

			.items.style2.medium > * {
				padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
				width: 50%;
			}

				.items.style2.medium > *:nth-child(-n + 2) {
					border-top-width: 0;
				}

				.items.style2.medium > *:nth-child(2n + 1) {
					border-left-width: 0;
				}

			.items.style2.small > *:nth-child(-n + 3) {
				border-top-width: 1px;
			}

			.items.style2.small > *:nth-child(3n + 1) {
				border-left-width: 1px;
			}

			.items.style2.small > * {
				padding: 3.5rem 3.5rem 1.5rem 3.5rem ;
				width: 50%;
			}

				.items.style2.small > *:nth-child(-n + 2) {
					border-top-width: 0;
				}

				.items.style2.small > *:nth-child(2n + 1) {
					border-left-width: 0;
				}

		}

		@media screen and (max-width: 480px) {

			.items.style2.big > *:nth-child(-n + 2) {
				border-top-width: 1px;
			}

			.items.style2.big > *:nth-child(2n + 1) {
				border-left-width: 1px;
			}

			.items.style2.big > * {
				padding: 2.625rem 2.625rem 0.625rem 2.625rem ;
				width: 100%;
			}

				.items.style2.big > *:nth-child(-n + 1) {
					border-top-width: 0;
				}

				.items.style2.big > *:nth-child(1n + 1) {
					border-left-width: 0;
				}

			.items.style2.medium > *:nth-child(-n + 2) {
				border-top-width: 1px;
			}

			.items.style2.medium > *:nth-child(2n + 1) {
				border-left-width: 1px;
			}

			.items.style2.medium > * {
				padding: 2.625rem 2.625rem 0.625rem 2.625rem ;
				width: 100%;
			}

				.items.style2.medium > *:nth-child(-n + 1) {
					border-top-width: 0;
				}

				.items.style2.medium > *:nth-child(1n + 1) {
					border-left-width: 0;
				}

			.items.style2.small > *:nth-child(-n + 2) {
				border-top-width: 1px;
			}

			.items.style2.small > *:nth-child(2n + 1) {
				border-left-width: 1px;
			}

			.items.style2.small > * {
				padding: 2.625rem 2.625rem 0.625rem 2.625rem ;
				width: 100%;
			}

				.items.style2.small > *:nth-child(-n + 1) {
					border-top-width: 0;
				}

				.items.style2.small > *:nth-child(1n + 1) {
					border-left-width: 0;
				}

		}

/* Items (style3) */

	.items.style3 {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		margin: 3rem 0;
		position: relative;
	}

		.items.style3 > * {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
		}

		.items.style3.big > * {
			padding: 1.75rem 1.75rem 0.1rem 1.75rem ;
			width: 50%;
		}

		.items.style3.medium > * {
			padding: 1.09375rem 1.09375rem 0.1rem 1.09375rem ;
			width: 33.33333%;
		}

		.items.style3.small > * {
			padding: 0.65625rem 0.65625rem 0.1rem 0.65625rem ;
			width: 25%;
		}

		@media screen and (max-width: 1280px) {

			.items.style3.small > * {
				padding: 1.09375rem 1.09375rem 0.1rem 1.09375rem ;
				width: 33.33333%;
			}

		}

		@media screen and (max-width: 980px) {

			.items.style3.medium > * {
				padding: 1.75rem 1.75rem 0.1rem 1.75rem ;
				width: 50%;
			}

			.items.style3.small > * {
				padding: 1.75rem 1.75rem 0.1rem 1.75rem ;
				width: 50%;
			}

		}

		@media screen and (max-width: 736px) {

			.items.style3 {
				margin: 2rem 0;
			}

		}

		@media screen and (max-width: 480px) {

			.items.style3.big > * {
				padding: 1.3125rem 1.3125rem 0.1rem 1.3125rem ;
				width: 100%;
			}

			.items.style3.medium > * {
				padding: 1.3125rem 1.3125rem 0.1rem 1.3125rem ;
				width: 100%;
			}

			.items.style3.small > * {
				padding: 1.3125rem 1.3125rem 0.1rem 1.3125rem ;
				width: 100%;
			}

			.items.style3.big > *, .items.style3.medium > *, .items.style3.small > * {
				padding-left: 0;
				padding-right: 0;
			}

			.items.style3.big > :first-child, .items.style3.medium > :first-child, .items.style3.small > :first-child {
				padding-top: 0;
			}

			.items.style3.big > :last-child, .items.style3.medium > :last-child, .items.style3.small > :last-child {
				padding-bottom: 0;
			}

				.items.style3.big > :last-child > .inner > :last-child, .items.style3.medium > :last-child > .inner > :last-child, .items.style3.small > :last-child > .inner > :last-child {
					margin-bottom: 0;
				}

		}

	.items.style1 > * {
		border-color: rgba(0, 0, 0, 0.2);
	}

	.items.style2 {
		border-color: rgba(0, 0, 0, 0.2);
	}

		.items.style2 > * {
			border-color: rgba(0, 0, 0, 0.2);
		}

/* Index */

	.index > * {
		padding: 3rem 0 1rem 0 ;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		border-top: solid 1px;
	}

		.index > * > header {
			-moz-flex-grow: 0;
			-webkit-flex-grow: 0;
			-ms-flex-grow: 0;
			flex-grow: 0;
			-moz-flex-shrink: 0;
			-webkit-flex-shrink: 0;
			-ms-flex-shrink: 0;
			flex-shrink: 0;
			width: 15rem;
		}

		.index > * > .content {
			-moz-flex-grow: 1;
			-webkit-flex-grow: 1;
			-ms-flex-grow: 1;
			flex-grow: 1;
			-moz-flex-shrink: 1;
			-webkit-flex-shrink: 1;
			-ms-flex-shrink: 1;
			flex-shrink: 1;
		}

	.index > :first-child {
		border-top: 0;
	}

	@media screen and (max-width: 980px) {

		.index > * > header {
			width: 11rem;
		}

	}

	@media screen and (max-width: 736px) {

		.index > * > header {
			width: 10rem;
		}

	}

	@media screen and (max-width: 480px) {

		.index > * {
			-moz-flex-direction: column;
			-webkit-flex-direction: column;
			-ms-flex-direction: column;
			flex-direction: column;
		}

			.index > * > header {
				width: 100%;
			}

	}

	.index > * {
		border-top-color: rgba(0, 0, 0, 0.2);
	}

/* Wrapper */

	#wrapper {
		background-color: inherit;
		width: 100%;
		overflow-x: hidden;
	}

		#wrapper > .invert {
			background-color: #000000;
			color: #ffffff;
		}

			#wrapper > .invert input, #wrapper > .invert select, #wrapper > .invert textarea {
				color: #ffffff;
			}

			#wrapper > .invert a {
				color: #ffffff;
			}

				#wrapper > .invert a:hover {
					color: #47D3E5;
				}

			#wrapper > .invert strong, #wrapper > .invert b {
				color: #ffffff;
			}

			#wrapper > .invert h1, #wrapper > .invert h2, #wrapper > .invert h3, #wrapper > .invert h4, #wrapper > .invert h5, #wrapper > .invert h6 {
				color: #ffffff;
			}

			#wrapper > .invert blockquote {
				border-left-color: white;
			}

			#wrapper > .invert code {
				background: rgba(255, 255, 255, 0.125);
				border-color: white;
			}

			#wrapper > .invert hr {
				border-bottom-color: white;
			}

			#wrapper > .invert .box {
				border-color: white;
			}

			#wrapper > .invert input[type="submit"],
			#wrapper > .invert input[type="reset"],
			#wrapper > .invert input[type="button"],
			#wrapper > .invert button,
			#wrapper > .invert .button {
				background-color: transparent;
				box-shadow: inset 0 0 0 1px white;
				color: #ffffff !important;
			}

				#wrapper > .invert input[type="submit"]:hover,
				#wrapper > .invert input[type="reset"]:hover,
				#wrapper > .invert input[type="button"]:hover,
				#wrapper > .invert button:hover,
				#wrapper > .invert .button:hover {
					box-shadow: inset 0 0 0 1px #47D3E5;
					color: #47D3E5 !important;
				}

				#wrapper > .invert input[type="submit"]:active,
				#wrapper > .invert input[type="reset"]:active,
				#wrapper > .invert input[type="button"]:active,
				#wrapper > .invert button:active,
				#wrapper > .invert .button:active {
					background-color: rgba(71, 211, 229, 0.2);
					box-shadow: inset 0 0 0 1px #47D3E5;
					color: #47D3E5 !important;
				}

				#wrapper > .invert input[type="submit"].primary,
				#wrapper > .invert input[type="reset"].primary,
				#wrapper > .invert input[type="button"].primary,
				#wrapper > .invert button.primary,
				#wrapper > .invert .button.primary {
					background-color: #ffffff;
					box-shadow: none;
					color: #000000 !important;
				}

					#wrapper > .invert input[type="submit"].primary:hover,
					#wrapper > .invert input[type="reset"].primary:hover,
					#wrapper > .invert input[type="button"].primary:hover,
					#wrapper > .invert button.primary:hover,
					#wrapper > .invert .button.primary:hover {
						background-color: #47D3E5;
					}

					#wrapper > .invert input[type="submit"].primary:active,
					#wrapper > .invert input[type="reset"].primary:active,
					#wrapper > .invert input[type="button"].primary:active,
					#wrapper > .invert button.primary:active,
					#wrapper > .invert .button.primary:active {
						background-color: #1ebdd1;
					}

			#wrapper > .invert label {
				color: #ffffff;
			}

			#wrapper > .invert input[type="text"],
			#wrapper > .invert input[type="password"],
			#wrapper > .invert input[type="email"],
			#wrapper > .invert input[type="tel"],
			#wrapper > .invert input[type="search"],
			#wrapper > .invert input[type="url"],
			#wrapper > .invert select,
			#wrapper > .invert textarea {
				border-color: white;
			}

				#wrapper > .invert input[type="text"]:focus,
				#wrapper > .invert input[type="password"]:focus,
				#wrapper > .invert input[type="email"]:focus,
				#wrapper > .invert input[type="tel"]:focus,
				#wrapper > .invert input[type="search"]:focus,
				#wrapper > .invert input[type="url"]:focus,
				#wrapper > .invert select:focus,
				#wrapper > .invert textarea:focus {
					border-color: #47D3E5;
					box-shadow: 0 0 0 1px #47D3E5;
				}

			#wrapper > .invert select {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='40' height='40' preserveAspectRatio='none' viewBox='0 0 40 40'%3E%3Cpath d='M9.4,12.3l10.4,10.4l10.4-10.4c0.2-0.2,0.5-0.4,0.9-0.4c0.3,0,0.6,0.1,0.9,0.4l3.3,3.3c0.2,0.2,0.4,0.5,0.4,0.9 c0,0.4-0.1,0.6-0.4,0.9L20.7,31.9c-0.2,0.2-0.5,0.4-0.9,0.4c-0.3,0-0.6-0.1-0.9-0.4L4.3,17.3c-0.2-0.2-0.4-0.5-0.4-0.9 c0-0.4,0.1-0.6,0.4-0.9l3.3-3.3c0.2-0.2,0.5-0.4,0.9-0.4S9.1,12.1,9.4,12.3z' fill='rgba(0, 0, 0, 0.2)' /%3E%3C/svg%3E");
			}

				#wrapper > .invert select option {
					color: #000000;
					background: #ffffff;
				}

			#wrapper > .invert input[type="checkbox"] + label,
			#wrapper > .invert input[type="radio"] + label {
				color: #ffffff;
			}

				#wrapper > .invert input[type="checkbox"] + label:before,
				#wrapper > .invert input[type="radio"] + label:before {
					border-color: white;
				}

			#wrapper > .invert input[type="checkbox"]:checked + label:before,
			#wrapper > .invert input[type="radio"]:checked + label:before {
				background-color: #ffffff;
				border-color: #ffffff;
				color: #000000;
			}

			#wrapper > .invert input[type="checkbox"]:focus + label:before,
			#wrapper > .invert input[type="radio"]:focus + label:before {
				border-color: #47D3E5;
				box-shadow: 0 0 0 1px #47D3E5;
			}

			#wrapper > .invert ::-webkit-input-placeholder {
				color: #ffffff !important;
			}

			#wrapper > .invert :-moz-placeholder {
				color: #ffffff !important;
			}

			#wrapper > .invert ::-moz-placeholder {
				color: #ffffff !important;
			}

			#wrapper > .invert :-ms-input-placeholder {
				color: #ffffff !important;
			}

			#wrapper > .invert .icon.style2:before {
				box-shadow: inset 0 0 0 1px white;
			}

			#wrapper > .invert a.icon.style2:hover:before {
				box-shadow: inset 0 0 0 1px #47D3E5;
				color: #47D3E5;
			}

			#wrapper > .invert a.icon.style2:active:before {
				background-color: rgba(71, 211, 229, 0.1);
				box-shadow: inset 0 0 0 1px #47D3E5;
				color: #47D3E5;
			}

			#wrapper > .invert ul.alt li {
				border-top-color: white;
			}

			#wrapper > .invert header p {
				color: #ffffff;
			}

			#wrapper > .invert table tbody tr {
				border-color: white;
			}

				#wrapper > .invert table tbody tr:nth-child(2n + 1) {
					background-color: rgba(255, 255, 255, 0.125);
				}

				#wrapper > .invert table tbody tr.alt {
					background-color: rgba(255, 255, 255, 0.125) !important;
				}

			#wrapper > .invert table th {
				color: #ffffff;
			}

			#wrapper > .invert table thead {
				border-bottom-color: white;
			}

			#wrapper > .invert table tfoot {
				border-top-color: white;
			}

			#wrapper > .invert table.alt tbody tr td {
				border-color: white;
			}

			#wrapper > .invert table.uniform tbody tr:nth-child(2n + 1) {
				background-color: transparent;
			}

			#wrapper > .invert .banner .image {
				background-color: rgba(255, 255, 255, 0.125);
			}

			#wrapper > .invert .banner.style4 .image {
				border-color: white;
				background-color: white;
				border-width: 1px;
			}

				#wrapper > .invert .banner.style4 .image:before {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='11' y='12' width='42' height='8' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
					border-color: white;
					width: calc(100% + 2px);
					margin-left: -1px;
				}

				#wrapper > .invert .banner.style4 .image:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Ccircle cx='32' cy='16' r='14' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
					border-color: white;
					width: calc(100% + 2px);
					margin-left: -1px;
				}

			#wrapper > .invert .banner.style4.android .image:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='6' y='4' width='52' height='24' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			}

			#wrapper > .invert .spotlight .image {
				background-color: rgba(255, 255, 255, 0.125);
			}

			#wrapper > .invert .spotlight.style3 .image {
				border-color: white;
				background-color: white;
				border-width: 1px;
			}

				#wrapper > .invert .spotlight.style3 .image:before {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='11' y='12' width='42' height='8' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
					border-color: white;
					width: calc(100% + 2px);
					margin-left: -1px;
				}

				#wrapper > .invert .spotlight.style3 .image:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Ecircle %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Ccircle cx='32' cy='16' r='14' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
					border-color: white;
					width: calc(100% + 2px);
					margin-left: -1px;
				}

			#wrapper > .invert .spotlight.style3.android .image:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='64px' height='32px' viewBox='0 0 64 32' zoomAndPan='disable'%3E%3Cstyle%3Erect %7Bfill: transparent%3B stroke: white%3B stroke-width: 1px%3B %7D%3C/style%3E%3Crect rx='4' ry='4' x='6' y='4' width='52' height='24' vector-effect='non-scaling-stroke' /%3E%3C/svg%3E");
			}

			#wrapper > .invert .gallery article .image {
				background-color: rgba(255, 255, 255, 0.125);
			}

			#wrapper > .invert .items.style1 > * {
				border-color: white;
			}

			#wrapper > .invert .items.style2 {
				border-color: white;
			}

				#wrapper > .invert .items.style2 > * {
					border-color: white;
				}

			#wrapper > .invert .index > * {
				border-top-color: white;
			}

		#wrapper > .color1 {
			background-color: #30363d;
		}

		#wrapper > .color2 {
			background-color: #db8992;
		}

		#wrapper > .color3 {
			background-color: #ab7aad;
		}

		#wrapper > .color4 {
			background-color: #897cad;
		}

		#wrapper > .color5 {
			background-color: #7794ce;
		}

		#wrapper > .color6 {
			background-color: #64abb4;
		}

		#wrapper > .color7 {
			background-color: #6ba78c;
		}

		#wrapper.divided > * {
			box-shadow: inset 0 1px 0 0 rgba(0, 0, 0, 0.075);
		}

			#wrapper.divided > *:first-child {
				box-shadow: none !important;
			}

		#wrapper.divided > .invert {
			box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.125);
		}

			#wrapper.divided > .invert:first-child {
				box-shadow: none !important;
			}
