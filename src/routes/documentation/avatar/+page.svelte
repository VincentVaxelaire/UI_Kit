<script>
    import { Avatar, AvatarImg } from '$lib/components/avatar'

    const userAvatar = {src: './image/user.jpg', user: 'user1', link: './profil/user1'}
    const usersAvatars = [
        {src: './image/user.jpg', user: 'user1', link: './profil/user1'},
        {src: './image/user.jpg', user: 'user1', link: './profil/user2'},
        {src: './image/user.jpg', user: 'user1', link: './profil/user3'},
    ]
</script>

<Avatar link>
    <AvatarImg src alt>
        <svelte:fragment slot="image"></svelte:fragment>
    </AvatarImg>
</Avatar>