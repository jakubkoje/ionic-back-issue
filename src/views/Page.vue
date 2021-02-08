<template>
	<ion-page>
		<ion-header>
			<ion-toolbar>
				<ion-buttons>
					<ion-back-button></ion-back-button>
				</ion-buttons>
				<ion-title>Test</ion-title>
			</ion-toolbar>
		</ion-header>
		<ion-content>
			<ion-text>
				<h1>Test</h1>
			</ion-text>
		</ion-content>
	</ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import {
	IonPage,
	IonContent,
	IonHeader,
	IonTitle,
	IonText,
	IonToolbar,
	IonButtons,
	IonBackButton,
} from '@ionic/vue';
export default defineComponent({
	name: 'Page',
	components: {
		IonPage,
		IonContent,
		IonHeader,
		IonTitle,
		IonText,
		IonToolbar,
		IonButtons,
		IonBackButton,
	},
});
</script>