<template>
    <div class="row justify-content-center">
        <div class="col-md-6">
            <h1>Create Student</h1>
            <form action="">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" class="form-control" v-model="student.name" required>
                </div>
                 <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" class="form-control" v-model="student.email" required>
                </div>
                 <div class="form-group">
                    <label for="phone">Phone</label>
                    <input type="text" class="form-control" v-model="student.phone" required>
                </div>
                <div class="form-group">
                    <button class="btn btn-success btn-block">Create</button>
                </div>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{
            student:{
                name: '',
                email: '',
                phone: ''
            }
        }
    },
    methods:{
        handleSubmitForm(){}       
    }
}
</script>

