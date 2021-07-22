<script>
	import FeatureToggle from "../components/feature-toggle.svelte";
	import { FEATURE_TOGGLES } from "../feature-toggles";
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>1 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>2 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>3 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>4 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>5 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>6 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>7 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>8 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>9 Some people see this, others don't!</p>
</FeatureToggle>
<FeatureToggle name={FEATURE_TOGGLES.vipWelcome.name}>
	<p>10 Some people see this, others don't!</p>
</FeatureToggle>
