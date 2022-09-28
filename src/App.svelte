<script>
	import FeedbackList from './componets/FeedbackList.svelte';
	
		let feedback = [
	{
		id: 1,
		rating: 10,
		text: 'Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat',
	},
	{
		id: 2,
		rating: 9,
		text: 'Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat',
	},
	{
		id: 3,
		rating: 8,
		text: 'Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat',
	},
	]
</script>

<main>
	<FeedbackList {feedback} />
</main>
