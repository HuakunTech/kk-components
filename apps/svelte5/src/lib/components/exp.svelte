<script lang="ts">
	import { Accordion } from "@kksh/svelte5"
</script>

<Accordion.Root type="single" class="w-full sm:max-w-[70%] transition-all">
	<Accordion.Item value="item-1" class="transition-all">
		<Accordion.Trigger>Is it accessible?</Accordion.Trigger>
		<Accordion.Content>Yes. It adheres to the WAI-ARIA design pattern.</Accordion.Content>
	</Accordion.Item>
	<Accordion.Item value="item-2" class="transition-all">
		<Accordion.Trigger>Is it styled?</Accordion.Trigger>
		<Accordion.Content>
			Yes. It comes with default styles that matches the other components' aesthetic.
		</Accordion.Content>
	</Accordion.Item>
	<Accordion.Item value="item-3" class="transition-all">
		<Accordion.Trigger>Is it animated?</Accordion.Trigger>
		<Accordion.Content>
			Yes. It's animated by default, but you can disable it if you prefer.
		</Accordion.Content>
	</Accordion.Item>
</Accordion.Root>
